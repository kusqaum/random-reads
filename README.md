The `random-reads` python script generates random nucleotide FASTQ data.

## Usage

~~~python
usage: random-reads [-h] [-V] [-v {error,warning,info,debug}] [-l N] N

Generate random FASTQ data

positional arguments:
  N                     Number of reads to generate

options:
  -h, --help            show this help message and exit
  -V, --version         show program's version number and exit
  -v {error,warning,info,debug}, --verbose {error,warning,info,debug}
                        Set logging level (default warning
  -l N, --length N      Read length to yield
~~~