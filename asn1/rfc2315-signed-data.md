<pre>
SignedData ::= SEQUENCE {
    version              <a href="integer.md">INTEGER</a>,
    digestAlgorithms     DigestAlgorithmIdentifiers,
    contentInfo          <a href="rfc2315-content-info.md">ContentInfo</a>,
    certificates     [0] IMPLICIT ExtendedCertificatesAndCertificates OPTIONAL,
    crls             [1] IMPLICIT CertificateRevocationLists OPTIONAL,
    signerInfos          <a href="rfc2315-signer-infos.md">SignerInfos</a>
}

DigestAlgorithmIdentifiers ::= SET OF <a herf="algorithm-identifier.md">AlgorithmIdentifier</a>
ExtendedCertificatesAndCertificates ::= SET OF <a herf="rfc2315-extended-certificate-or-certificate.md">ExtendedCertificateOrCertificate</a>
</pre>
