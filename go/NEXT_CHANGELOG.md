# NEXT CHANGELOG

## Release v1.8.0

### New Features and Improvements

- Added `ArrowStreamConfigurationOptions.DictionaryHandling` for Arrow Flight
  streams. `ArrowDictionaryResend` sends dictionary-encoded columns as Arrow IPC
  dictionaries for the server to decode, instead of decoding them on the client.
  The default, `ArrowDictionaryHydrate`, keeps the existing behavior.

### Deprecations

### Bug Fixes

### Documentation

### Internal Changes

### API Changes
