<pre>
GeneralName ::= CHOICE {
    otherName                 [0]  <a href="rfc5280-another-name.md">AnotherName</a>,
    rfc822Name                [1]  <a href="ia5-string.md">IA5String</a>,
    dNSName                   [2]  <a href="ia5-string.md">IA5String</a>,
    x400Address               [3]  <a href="#">ORAddress</a>,
    directoryName             [4]  <a href="rfc5280-name.md">Name</a>,
    ediPartyName              [5]  <a href="rfc5280-edi-party-name.md">EDIPartyName</a>,
    uniformResourceIdentifier [6]  <a href="ia5-string.md">IA5String</a>,
    iPAddress                 [7]  <a href="octet-string.md">OCTET STRING</a>,
    registeredID              [8]  <a href="oid.md">OBJECT IDENTIFIER</a>
 }
</pre>
