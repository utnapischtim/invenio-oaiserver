..
    This file is part of Invenio.
    Copyright (C) 2016-2020 CERN.

    Invenio is free software; you can redistribute it and/or modify it
    under the terms of the MIT License; see LICENSE file for more details.

Changes
=======

Version 1.3.0 (released 2021-10-20)

- Unpin Flask version.

Version 1.2.2 (released 2021-09-17)

- Adds support for more easily integrating the OAI-PMH server in InvenioRDM.

- Adds new configuration variables for dependency injection of search class,
  ID fetcher, record getter tec.

- The release is fully backward compatibility and does not change any
  behaviour.

- Fixes a bug with Elasticsearch 7 causing invalid OAI-PMH output for the
  resumption token.

Version 1.2.1 (released 2021-07-12)

- Adds german translations

Version 1.2.0 (released 2020-03-17)

- Removes support for python 2.7
- Centralises management of Flask dependency via invenio-base

Version 1.1.2 (released 2019-07-19)

- fixes default config OAISERVER_QUERY_PARSER_FIELDS
- changes celery support module to invenio-celery

Version 1.1.1 (released 2019-07-31)

- Added support for Marshmallow v2 and v3.

Version 1.1.0 (released 2019-07-31)

- Added support for Eleasticsearch v7

Version 1.0.3 (released 2019-02-15)

- Pins marshmallow package to <3 in preparation for upcoming v3.0.0 release
  which will break compatibility.

Version 1.0.2 (released 2019-01-10)

- Improved performance of the *Identify* verb response by fetching earliest
  record date from Elasticsearch.

Version 1.0.1 (released 2018-12-14)

Version 1.0.0 (released 2018-03-23)

- Initial public release.
