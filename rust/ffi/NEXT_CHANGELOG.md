# NEXT CHANGELOG

## Release v1.10.0

### Major Changes

### New Features and Improvements

- **Arrow stream options (C API)**: `CArrowStreamConfigurationOptions.dictionary_handling`
  (`int32_t`) selects how dictionary-encoded columns are sent: `0` = Hydrate
  (decode them on the client, the default), `1` = Resend (send the dictionaries
  for the server to decode).

### Bug Fixes

### Documentation

### Internal Changes

### Behavior Changes

### Breaking Changes

### Deprecations

### API Changes

- Appended `dictionary_handling` to `CArrowStreamConfigurationOptions`, so
  callers must rebuild against the new `zerobus.h`. Zero-initialized options and
  `zerobus_arrow_get_default_config()` keep the Hydrate default.
