# Trimmomatic-pigz

A 10x faster version base on [official trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic). The results of trimmomatic-pigz are exactly the same with official trimmomatic.(md5sum with decompression fastq)

## Principle

We replaced gzip library with a parallelized version: pigz.

https://github.com/shevek/parallelgzip

> This library contains a parallelized GZIP implementation which is a high performance drop-in replacement for the standard java.util.zip classes. It is a pure Java equivalent of the pigz parallel compresssor.

## Benchmark test
