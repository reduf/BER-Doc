<pre>
TBSCertificate  ::=  SEQUENCE  {
    version          [0] EXPLICIT <a href="integer.md">INTEGER</a> DEFAULT 0,
    serialNumber         <a href="integer.md">INTEGER</a>,
    signature            <a href="algorithm-identifier.md">AlgorithmIdentifier</a>,
    issuer               <a href="rfc5280-name.md">Name</a>,
    validity             <a href="rfc5280-validity.md">Validity</a>,
    subject              <a href="rfc5280-name.md">Name</a>,
    subjectPublicKeyInfo <a href="rfc5280-subject-public-key-info.md">SubjectPublicKeyInfo</a>,
    issuerUniqueID   [1] IMPLICIT UniqueIdentifier OPTIONAL,
                         -- If present, version MUST be v2 or v3
    subjectUniqueID  [2] IMPLICIT UniqueIdentifier OPTIONAL,
                         -- If present, version MUST be v2 or v3
    extensions       [3] EXPLICIT Extensions OPTIONAL
                         -- If present, version MUST be v3
}
</pre>
