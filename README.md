# Trimmomatic-pigz

A 10x faster version base on [official trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic). The results of trimmomatic-pigz are exactly the same with official trimmomatic.(md5sum with decompression fastq)

Download: https://github.com/jaydenSen/Trimmomatic-pigz/releases/download/v1.0/trimmomatic-pigz.jar

## Principle

We replaced gzip library with a parallelized version: pigz.

https://github.com/shevek/parallelgzip

> This library contains a parallelized GZIP implementation which is a high performance drop-in replacement for the standard java.util.zip classes. It is a pure Java equivalent of the pigz parallel compresssor.

## Benchmark test

Test in paired end Mode with two fastq.gz(R1/R2):

![image](https://github.com/jaydenSen/Trimmomatic-pigz/raw/master/benchmark-test.png)

## License

A short snippet describing the license (MIT)

MIT © Cangsheng Shen
