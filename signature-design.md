## Signature Composition

The signature is composed of:

1. Canonicalized request parameters
2. Timestamp with second-level precision
3. A fixed-length hash output
4. Client-specific constant

These elements are concatenated in a deterministic order
before being passed into a cryptographic hash function.
