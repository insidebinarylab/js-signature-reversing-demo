## Entry Point Identification

The signature logic is triggered during request preparation.
By tracing the network initiator and setting breakpoints,
the following execution path was identified:

Request Builder → Parameter Normalization → Signature Function

## Obfuscation Strategy

- String array indirection
- Control flow flattening
- Runtime constant resolution
