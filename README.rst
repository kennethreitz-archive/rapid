Rapid: API Wrapper Framework
============================

:Author: Kenneth Reitz
:License: ISC


Features
--------

- Encoding/Decoding Mechanisms (JSON, YAML, etc)
- HTTP Basic, OAuth
- Pagination
- CachedEndpoint

rapid.Endpoint
rapid.CachedEndpoint
rapid.API
rapid.SyncedList


Simple::

    import rapid


    class GitHub(rapid.API):

        repos = rapid.Endpoint(models.Repo)


        def __init__(self, username=None, password=None):
            pass

        @api_property('')
        def repos()

        @property
        def repos():
            repos = rapid.CachedEndpoint()



Hmmmm::

    import rapid

    class GitHub(rapid.API):

        def __init__(self):
            pass

        def repos():

