+++
title = "NFS@Home"
tags = ["distributed computing" "math"]
+++

## NFS@Home

View the project [**here**](https://escatter11.fullerton.edu/nfs/).

### Overview

NFS@Home is a research project that uses Internet-connected computers to do the lattice sieving step in the Number Field Sieve factorization of large integers. As a young school student, you gained your first experience at breaking an integer into prime factors, such as 15 = 3 * 5 or 35 = 5 * 7. NFS@Home is a continuation of that experience, only with integers that are hundreds of digits long. Most recent large factorizations have been done primarily by large clusters at universities. With NFS@Home you can participate in state-of-the-art factorizations simply by downloading and running a free program on your computer.

Integer factorization is interesting from both mathematical and practical perspectives. Mathematically, for instance, the calculation of [multiplicative functions](http://en.wikipedia.org/wiki/Multiplicative_function) in number theory for a particular number require the factors of the number. Likewise, the integer factorization of particular numbers can aid in the proof that an associated number is prime. Practically, many public key algorithms, including the [RSA algorithm](http://en.wikipedia.org/wiki/RSA), rely on the fact that the publicly available modulus cannot be factored. If it is factored, the private key can be easily calculated. Until quite recently, RSA-512, which uses a 512-bit modulus (155 digits), was commonly used but can now be easily broken.

The numbers that we are factoring are chosen from the [Cunningham project](http://homes.cerias.purdue.edu/~ssw/cun/index.html). Started in 1925, it is one of the oldest continuously ongoing projects in computational number theory. The third edition of the book, published by the American Mathematical Society in 2002, is available as a [free download](http://www.ams.org/online_bks/conm22/). All results obtained since, including those of NFS@Home, are available on the Cunningham project website.

### Runs on:
- Linux
- MacOS
- Windows
