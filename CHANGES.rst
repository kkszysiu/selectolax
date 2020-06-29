selectolax Changelog
====================

Version 0.2.5
-------------

-   Add `node_replace_with`, `node_insert_before` and `node_insert_after` methods
-   Add `insert_before` and `insert_after` methods

Version 0.2.4
-------------

Released

-   Set maximum input size to 80MB
-   Update modest

Version 0.2.3
-------------

Released

-   Rebuild PyPi wheels to support Python 3.8 and manylinux2010


Version 0.2.2
-------------

Released

-   Fix node comparison

Version 0.2.1
-------------

Released

-   Add optional `include_text` parameter for the `iter` and `traverse` methods

Version 0.2.0
-------------

Released

-   Fix `iter()` does not yield text nodes
-   Switch from TravisCI to Github Actions
-   Build and ship wheels for Windows, MacOS and Linux using Azure Pipelines
-   Add `unwrap` and `unwrap_tags` method (`#7`_ )
-   Add `replace_with` method (`#13`_ )
-   Add `attrs` property
-   Add `traverse` method

.. _#7: https://github.com/rushter/selectolax/issues/7
.. _#13: https://github.com/rushter/selectolax/issues/13
