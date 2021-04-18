# agoncal-sample-asciidoc-cover

How to have a different cover for each format (PDF, EPUB, HTML).
Asciidoc uses two attributes to handle front and back cover (`:front-cover-image:` and `:back-cover-image:`).
But not every format has a front and/or back cover.

## Formats and covers

| Format | Front Cover | Back Cover |
| --------------- | --------------- | --------------- |
| PDF | Yes | Yes |
| EPUB | Yes | No |
| HTML | No| No |

## References

* [backends](https://docs.asciidoctor.org/asciidoctorj/latest/asciidoctor-api-options/#backend)
* [document_test.rb](https://github.com/asciidoctor/asciidoctor/blob/master/test/document_test.rb)
