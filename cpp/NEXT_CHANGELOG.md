# NEXT CHANGELOG

## Release v0.5.0

### New Features and Improvements

- Added `ArrowStreamOptions::dictionary_handling` (`ArrowDictionaryHandling`).
  `ArrowDictionaryHandling::Resend` sends dictionary-encoded columns as Arrow IPC
  dictionaries for the server to decode, instead of decoding them on the client.
  The default, `Hydrate`, keeps the existing behavior.

### Bug Fixes

### Documentation

### Internal Changes

### Breaking Changes

### Deprecations

### API Changes
