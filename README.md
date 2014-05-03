## Description

In 2012 I wrote my [article](http://www.strozhevsky.com/free_docs/asn1_in_simple_words.pdf) about ASN.1. Right after I finished it I recognized that there are no really free ASN.1:2008 test suites. Because of (IMHO) there are many errors/mistakes/misunderstandings in existing ASN.1 coders/decoders. The test suite I am placing here is intended to be a "helper" for better ASN.1:2008 understanding and further implementation of coders/decoders. As a "test plant" for my test suite I made a freely available [C++ ASN.1:2008 coder/decoder](https://github.com/YuryStrozhevsky/C-plus-plus-ASN.1-2008-coder-decoder). All *.xml files in my test suite are output from my [coder/decoder](https://github.com/YuryStrozhevsky/C-plus-plus-ASN.1-2008-coder-decoder).

## Usage

1. Read "pdf/free_asn1_testsuite.pdf" file
2. Use "suite/*.ber" files for testing decoding functionality;
3. Use "suite/*.xml" file as a suspected output from decoding;
4. With my [coder/decoder](https://github.com/YuryStrozhevsky/C-plus-plus-ASN.1-2008-coder-decoder) you can use "suite/*.xml" files also as an input for testing encoding functionality;

## License

Copyright (c) 2014, [Yury Strozhevsky](http://www.strozhevsky.com/)
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.