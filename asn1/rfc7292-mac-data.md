<pre>
MacData ::= SEQUENCE {
   mac         DigestInfo,
   macSalt     <a href="octet-string.md">OCTET STRING</a>,
   iterations  <a href="integer.md">INTEGER</a> DEFAULT 1
   -- Note: The default is for historical reasons and its
   --       use is deprecated.
}
</pre>
