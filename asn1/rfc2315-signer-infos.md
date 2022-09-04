<pre>
SignerInfo ::= SEQUENCE {
    version                       <a href="integer.md">INTEGER</a>,
    issuerAndSerialNumber         <a href="rfc2315-issuer-and-serial-number.md">IssuerAndSerialNumber</a>,
    digestAlgorithm               <a href="algorithm-identifier.md">AlgorithmIdentifier</a>,
    authenticatedAttributes   [0] IMPLICIT SET OF <a href="rfc5280-attribute.md">Attribute</a> OPTIONAL,
    digestEncryptionAlgorithm     <a href="algorithm-identifier.md">AlgorithmIdentifier</a>,
    encryptedDigest               <a href="octet-string.md">OCTET STRING</a>,
    unauthenticatedAttributes [1] IMPLICIT SET OF <a href="rfc5280-attribute.md">Attribute</a> OPTIONAL
}
</pre>
