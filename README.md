# `fastq-join`

This is the work of:

Erik Aronesty (2013). TOBioiJ : "Comparison of Sequencing Utility Programs", DOI:10.2174/1875036201307010001

# Changes

 The Versioning here is awful. I've bumped the version with no major changes
 or bug fixes to the original algorithm.

# Build

```
git clone https://github.com/brwnj/fastq-join
cd fastq-join
make
```

Some tests are failing when building on OS X versus Redhat 6.6. OS X gives
"nan" while Redhat gives "-nan".

# Example Usage

```
fastq-join -p 2 -m 200 test_R1.fastq test_R2.fastq -o test_%.fastq
```
