---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - python

toc_footers:
  - <a href='javascript:alert('API keys are currently unavailable')'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true

code_clipboard: true
---

# Introduction

Welcome to the Cosmos Bots API! You can use our API to access Cosmos Bots API endpoints, which can get information on licenses, drops and our monitors.

We currently only have language bindings in Python. More are planned to come in the future.

# Authentication

> To authorize, use this code:

```python
import cosmosbots

api = cosmosbots.authorize('authkey')
```

> Make sure to replace `authkey` with your API key.

Cosmos Bots uses API keys to allow access to most API endpoints.

The API key is expected to be included in all API requests to the server which require it in a header that looks like the following:

`Authorization: authkey`

<aside class="notice">
You must replace <code>authkey</code> with your personal API key.
</aside>

# Examples

Coming soon!
