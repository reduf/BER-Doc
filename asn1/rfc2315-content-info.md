<pre>
ContentInfo ::= SEQUENCE {
    contentType     <a href="oid.md">ContentType</a>,
    content     [0] EXPLICIT ANY DEFINED BY contentType OPTIONAL
}

ContentType ::= <a href="oid.md">OBJECT IDENTIFIER</a>
</pre>
