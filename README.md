# Open Hospital - Doc

This project contains the administrator and user documentation of the [Open Hospital][openhospital] project in Asciidoc format.

- [Admin Manual][adminmanual] (`doc_admin/AdminManual.adoc`)
- [User Manual][usermanual] (`doc_user/UserManual.adoc`)

## How to build

To build the documentation you'll need Ruby 2.3+, `asciidoctor` and `asciidoctor-pdf`, which you can install through `gem` with `gem install asciidoctor-pdf --pre`.  

To create PDF documentation issue:

    asciidoctor-pdf nomeFile.adoc [-o path/to/nomeFile.pdf]
    
To create HTML documentation issue:

    asciidoctor nomeFile.adoc

## How to contribute

You can find the contribution guidelines in the [Open Hospital wiki][contribution-guide].  
A list of open issues is available on [Jira][jira].

 [openhospital]: https://www.open-hospital.org/
 [adminmanual]: https://github.com/informatici/openhospital-doc/blob/develop/doc_admin/AdminManual.adoc
 [usermanual]: https://github.com/informatici/openhospital-doc/tree/develop/doc_user
 [contribution-guide]: https://openhospital.atlassian.net/wiki/display/OH/Contribution+Guidelines
 [jira]: https://openhospital.atlassian.net/issues/
