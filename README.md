## Requirements

PHPWord requires the following:

- PHP 7.1+
- [XML Parser extension](http://www.php.net/manual/en/xml.installation.php)
- [Laminas Escaper component](https://docs.laminas.dev/laminas-escaper/intro/)
- [Zip extension](http://php.net/manual/en/book.zip.php) (optional, used to write OOXML and ODF)
- [GD extension](http://php.net/manual/en/book.image.php) (optional, used to add images)
- [XMLWriter extension](http://php.net/manual/en/book.xmlwriter.php) (optional, used to write OOXML and ODF)
- [XSL extension](http://php.net/manual/en/book.xsl.php) (optional, used to apply XSL style sheet to template )
- [dompdf library](https://github.com/dompdf/dompdf) (optional, used to write PDF)

## Installation

PHPWord is installed via [Composer](https://getcomposer.org/).
To [add a dependency](https://getcomposer.org/doc/04-schema.md#package-links) to PHPWord in your project, either

Run the following to use the latest stable version
```sh
composer require enreach-nl/phpword
```
