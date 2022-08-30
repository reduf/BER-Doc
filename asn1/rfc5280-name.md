<pre>
Name ::= CHOICE {
     rdnSequence  RDNSequence
}

RDNSequence ::= SEQUENCE OF RelativeDistinguishedName

RelativeDistinguishedName ::= SET SIZE (1..MAX) OF AttributeTypeAndValue

AttributeTypeAndValue ::= SEQUENCE {
     type     <a href="oid.md">AttributeType</a>,
     value    AttributeValue
}

AttributeType ::= <a href="oid.md">OBJECT IDENTIFIER</a>

AttributeValue ::= ANY -- DEFINED BY AttributeType
</pre>
