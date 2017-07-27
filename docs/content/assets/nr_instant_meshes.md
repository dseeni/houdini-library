+++
title = "NR Instant Meshes"
+++

<img align="right" src="https://img.shields.io/badge/Houdini-Indie-orange.svg">

&mdash; Wrapper for the [Instant Meshes][0] command-line interface.

  [0]: https://github.com/wjakob/instant-meshes

This digital asset can feed your geometry into [Instant Meshes][0] and
read the result back into Houdini. The Instant Meshes executables are
bundled with the asset for Windows, macOS and Linux.

When the asset is first used, it will unpack the Instant Meshes executable
into your Houdini preferences directory.

## Todolist

* Support Singularities and Edge constraints

## Screenshots

<p align="center"><img src="https://i.imgur.com/uS1ROqs.png"></p>
<p align="center"><img src="https://i.imgur.com/MLXhMBq.png"></p>
<p align="center"><img src="https://i.imgur.com/ulsnjrL.jpg"></p>

## Changelog

* v2
  * Suppress Instant Mesh console window popping up when the node is cooking
* v1
  * Initial version

## Acknowledgements

```
Instant Meshes
==============

Copyright (c) 2015 Wenzel Jakob, Daniele Panozzo, Marco Tarini,
and Olga Sorkine-Hornung. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors
   may be used to endorse or promote products derived from this software
   without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

You are under no obligation whatsoever to provide any bug fixes, patches, or
upgrades to the features, functionality or performance of the source code
("Enhancements") to anyone; however, if you choose to make your Enhancements
available either publicly, or directly to the authors of this software, without
imposing a separate written license agreement for such Enhancements, then you
hereby grant the following license: a non-exclusive, royalty-free perpetual
license to install, use, modify, prepare derivative works, incorporate into
other computer software, distribute, and sublicense such enhancements or
derivative works thereof, in binary and source code form.
```