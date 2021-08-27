Types of DBT models:
* Sources
* Staging
* Intermediate
* Facts
* Dimensions



Testing
* Data tests - specific
* Schema tests - generalized
* Custom schema tests (Requires Jinja + Macros)

Tests shipped with DBT:
* unique
* not_null
* accepted_values
* relationships

Notes:
* Models must be materialized before testing