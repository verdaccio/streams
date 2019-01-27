# Streams

[![CircleCI](https://circleci.com/gh/verdaccio/streams.svg?style=svg)](https://circleci.com/gh/ayusharma/verdaccio-memory)
[![codecov](https://codecov.io/gh/verdaccio/streams/branch/master/graph/badge.svg)](https://codecov.io/gh/verdaccio/verdaccio-memory)
[![verdaccio (latest)](https://img.shields.io/npm/v/@verdaccio/streams/latest.svg)](https://www.npmjs.com/package/verdaccio-memory)
[![backers](https://opencollective.com/verdaccio/tiers/backer/badge.svg?label=Backer&color=brightgreen)](https://opencollective.com/verdaccio)
[![discord](https://img.shields.io/discord/388674437219745793.svg)](http://chat.verdaccio.org/)
![MIT](https://img.shields.io/github/license/mashape/apistatus.svg)
[![node](https://img.shields.io/node/v/@verdaccio/streams/latest.svg)](https://www.npmjs.com/package/verdaccio-memory)



This project provides an extension of `PassThrough` stream.

It provides 2 additional methods `abort()` and `done()`. Those implementations are widely use in the verdaccio core for handle `tarballs`.