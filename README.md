# Fingerprintjs2sync

This is a fork of [Fingerprintjs2](https://github.com/Valve/fingerprintjs2). Back then Fingerprintjs2 looked like it was not maintained anymore ([which was not correct](https://github.com/valnub/fingerprintjs2sync/issues/1)) but I needed a synchronously working version of this lib, so here it is. Note that I had to remove Flash/Swf Font support but who still uses Flash in 2020, eh?

### Installation

```
yarn add fingerprintjs2sync
```

### Usage

```js
import Fingerprint2 from 'fingerprintjs2sync';

const fprint = (new Fingerprint2()).getSync().fprint;
```

See https://github.com/Valve/fingerprintjs2 for more info

#### License: MIT
