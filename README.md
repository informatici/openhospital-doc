# Open Hospital - Documentation

This project contains the administrator and user documentation of the [Open Hospital][openhospital] project in [AsciiDoc][asciidoc] format.

- [Admin Manual][adminmanual] (`doc_admin/AdminManual.adoc`)
- [User Manual][usermanual] (`doc_user/UserManual.adoc`)

## How to build

To build the documentation you will need [Ruby][ruby] 2.3+, `asciidoctor` and `asciidoctor-pdf`, which you can install through `gem` with `gem install asciidoctor-pdf --pre`.  

To create PDF documentation issue the command:

    asciidoctor-pdf fileName.adoc [-o path/to/fileName.pdf]
    
To create HTML documentation issue the command

    asciidoctor fileName.adoc

## How to contribute

You can find the contribution guidelines in the [Open Hospital wiki][contribution-guide].  
A list of open issues is available on [Jira][jira].

 [openhospital]: https://www.open-hospital.org/
 [adminmanual]: https://github.com/informatici/openhospital-doc/blob/develop/doc_admin/AdminManual.adoc
 [usermanual]: https://github.com/informatici/openhospital-doc/tree/develop/doc_user
 [contribution-guide]: https://openhospital.atlassian.net/wiki/display/OH/Contribution+Guidelines
 [jira]: https://openhospital.atlassian.net/jira/software/c/projects/OP/issues/
 [asciidoc]: https://asciidoc.org/
 [ruby]: https://www.ruby-lang.org/en/
