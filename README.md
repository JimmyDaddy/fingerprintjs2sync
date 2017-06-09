# Fingerprintjs2sync

The original [Fingerprintjs2](https://github.com/Valve/fingerprintjs2) is currently not maintained but I needed a synchronously working version of this lib, so here it is. Note that I had to remove Flash/Swf Font support but who still Flash in 2017, eh?

### Installation

```
yarn add fingerprintjs2sync
```

### Usage

```js
const fprint = (new Fingerprint2()).getSync().fprint;
```

See https://github.com/Valve/fingerprintjs2 for more info

#### License: MIT or Apache, whichever you prefer.
