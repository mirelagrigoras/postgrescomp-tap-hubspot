# Changelog
0.0.1
- **FEATURES:**
  - Added the `"max_pages_retrieved" ` configuration option.
  - Limited the number of records retrieved in an API call (where possible).

1.0.1
- **Fix:**
  - Removed max_pages_retrieved in sync_entity_chunked.

1.0.2:
- **Fix:**
  - Removed max_pages_retrieved since the replication_method for some streams is 'FULL_TABLE'. 