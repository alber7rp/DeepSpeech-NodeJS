# DeepSpeech - NodeJS

## Setup

1. Install dependencies via ```npm```:

```
$ npm install
```

2. Install [Sox - Sound eXchange](http://sox.sourceforge.net/) (code sample has been tested with version ```14.4.2``` of Sox).

3. On Windows, add ```sox.exe``` to the PATH environment variable.

4. Download the following models for *DeepSpeech*, and place them in the ```/models``` folder:

```
https://github.com/mozilla/DeepSpeech/releases/download/v0.8.0/deepspeech-0.8.0-models.pbmm
https://github.com/mozilla/DeepSpeech/releases/download/v0.8.0/deepspeech-0.8.0-models.scorer
```

*Note: check both models are correctly referenced inside ```index.js```.*

## See also

* [Official examples of DeepSpeech from Mozilla on GitHub](https://github.com/mozilla/DeepSpeech-examples/tree/r0.8/nodejs_wav)