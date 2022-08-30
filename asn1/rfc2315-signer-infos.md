<pre>
SignerInfo ::= SEQUENCE {
    version                       Version,
    issuerAndSerialNumber         IssuerAndSerialNumber,
    digestAlgorithm               <a href="algorithm-identifier.md">AlgorithmIdentifier</a>,
    authenticatedAttributes   [0] IMPLICIT Attributes OPTIONAL,
    digestEncryptionAlgorithm     <a href="algorithm-identifier.md">AlgorithmIdentifier</a>,
    encryptedDigest               EncryptedDigest,
    unauthenticatedAttributes [1] IMPLICIT Attributes OPTIONAL
}
</pre>
