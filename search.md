# Search
Developer Studio will do a full text search on tenant's data in the back end. DevStudio users can query and filter the data in many forms, such as by Capability, Region, Business type, etc.

## Caching
The most frequent requested resources will get cached to improve services speed. A Redis entry will get inserted if requested resource not available in cache. We generally cache information such as markdown documents and tenant configuration documents which are not updated too often.

For these caches, we have setup [webhooks](glossary.md#webhook) to handle the change and immediately update the cache should it detect that a tenant has pushed a Pull Request on their Github repository that makes a change to any of the cache's file(s).

## Indexing
Indexing crawler will visit each tenant's repo on the mentioned time intervals to scan and update indexes with new data if anything got changed.
The indexing time frequency is following on each env:

### Frequency of updates
  | Environment | Indexing frequency          |
  | ----------- | ------------------          |
  | Dev         | Every two hours             |
  | QA          | Every two hours             |
  | Stage       | Daily, 05:00PM ET           |
  | Production  | Daily, 11:00AM & 04:00PM ET |
