new-website
===========

Website of https://cdnjs.com, for the cdn content, see [cdnjs/cdnjs](https://github.com/cdnjs/cdnjs) repo.

[![Dependency Status](https://david-dm.org/cdnjs/new-website.svg?theme=shields.io)](https://david-dm.org/cdnjs/new-website)

## Dependencies

* [Node](https://nodejs.org)

## Setup

```sh
cd path/to/repo
npm install
```

## Running

```sh
npm install                 # install nodejs dependencies
export APP=[mainSite|api]   # chose which server you want to run
export LOCAL=true           # local mode will disable the global.gc() function and CSP header
./runServer.sh
```

**Note**:

  * The artifacts/meta data is on the [meta](https://github.com/cdnjs/new-website/tree/meta) branch.
