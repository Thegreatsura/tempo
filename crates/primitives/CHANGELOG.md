# Changelog

## `tempo-primitives@1.6.0`

### Minor Changes

- Implement TIP-1011 enhanced access key permissions with exact permission matching for keychain operations. (by @ArseniiKulikov, [#3444](https://github.com/Thegreatsura/tempo/pull/3444))

### Patch Changes

- Add call-scope support to keychain SDK: `authorize_key`, `revoke_key`, `set_allowed_calls`, `CallScopeBuilder`, and `KeyRestrictions` builders. Extend `TempoTransactionRequest` with key-type, key-data, and key-authorization builder methods. (by @ArseniiKulikov, [#3444](https://github.com/Thegreatsura/tempo/pull/3444))

