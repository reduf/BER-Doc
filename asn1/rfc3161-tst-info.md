<pre>
TSTInfo ::= SEQUENCE  {
    version        <a href="integer.md">INTEGER</a>,
    policy         <a href="oid.md">OBJECT IDENTIFIER</a>,
    messageImprint <a href="rfc3161-message-imprint.md">MessageImprint</a>,
                   -- MUST have the same value as the similar field in
                   -- TimeStampReq
    serialNumber   <a href="integer.md">INTEGER</a>,
                   -- Time-Stamping users MUST be ready to accommodate integers
                   -- up to 160 bits.
    genTime        <a href="generalize-time.md">GeneralizedTime</a>,
    accuracy       <a href="rfc3161-accuracy.md.md">Accuracy</a>                 OPTIONAL,
    ordering       <a href="boolean.md">BOOLEAN</a>             DEFAULT FALSE,
    nonce          <a href="integer.md">INTEGER</a>                  OPTIONAL,
                   -- MUST be present if the similar field was present
                   -- in TimeStampReq.  In that case it MUST have the same value.
     tsa          [0] <a href="rfc5280-general-name.md">GeneralName</a>           OPTIONAL,
    extensions    [1] IMPLICIT Extensions   OPTIONAL
}
</pre>
