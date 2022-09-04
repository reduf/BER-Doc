<pre>
DirectoryString ::= CHOICE {
    teletexString     TeletexString (SIZE (1..MAX)),
    printableString   <a href="printable_string.md">PrintableString</a> (SIZE (1..MAX)),
    universalString   <a href="universal_string.md">UniversalString</a> (SIZE (1..MAX)),
    utf8String        <a href="utf8_string.md">UTF8String</a> (SIZE (1..MAX)),
    bmpString         <a href="bmp_string.md">BMPString</a> (SIZE (1..MAX))
}
</pre>
