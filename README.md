# Fingerprintjs2Sync

## Synchronous Version of Fingerprintjs

This is a fork of [Fingerprintjs](https://github.com/fingerprintjs/fingerprintjs). I had to create this fork back then in 2017 as I needed a synchronously working version of Fingerprintjs, so here it is. Note that I had to remove Flash/Swf Font support but who still uses Flash in 2020, eh? Also, the original maintainer [suggest](https://github.com/valnub/fingerprintjs2sync/issues/1) to better not rely on synchronous methods if you can, so use at own risk.

### Installation

```
yarn add fingerprintjs2sync
```

### Usage

```js
import Fingerprint2 from 'fingerprintjs2sync';

const fprint = (new Fingerprint2()).getSync().fprint;
```

See https://github.com/Valve/fingerprintjs for more info

### License (MIT)

This software was forked in 2017 by [Timo Ernst](https://www.timo-ernst.net/contact/) based on the original [Fingerprintjs](https://github.com/fingerprintjs/fingerprintjs)
- Copyright (c) [Valentin Vasilyev](mailto:valentin.vasilyev@outlook.com), 2015
- Copyright (c) [Jonas Haag](mailto:jonas@lophus.org), 2018
- Copyright (c) [FingerprintJS, Inc](https://fingerprintjs.com), 2020
- Licensed under the [MIT license](http://www.opensource.org/licenses/mit-license.php).

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL FINGERPRINTJS INC OR TIMO ERNST BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF
THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
