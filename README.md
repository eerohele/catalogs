# XML Catalogs

An [Ant][ant] & [Ivy][ivy] build for downloading commonly used XML and HTML
schemas.

## Installation

1. Install Ant and Ivy if not already installed.
2. Run:

    ```bash
    $ git clone https://github.com/eerohele/markup-schemas.git
    $ cd markup-schemas
    $ ant
    ```

3. (*Optional*) Set your [`XML_CATALOG_FILES`][xml-catalog-files] environment
   variable to point to the `catalog.xml` file in the repo.

[ant]: https://ant.apache.org
[ivy]: https://ant.apache.org/ivy
[xml-catalog-files]: http://www.xmlsoft.org/catalog.html
