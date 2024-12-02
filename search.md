# Search
Developer Studio will do a full text search on tenant's data by using Elastic Search in the back end. Dev Studio users can query and filter the data in many forms, such as Customer Segments, Integration Types, etc...


# Indexing
Indexing crawler will visit each tenant's repo on the mentioned time intervals to scan and update indexes with new data if anything got changed.
The indexing time frequency is following on each env:


# Caching
The most frequent requested resources will get cached to improve services speed. A Redis entry will get inserted if requested resource not available in cache. 


# Frequency of updates
| Environment|Indexing frequency|
|-----------|-----------|
|Dev|Every one hour|
|QA|Daily once|
|Stage|Daily once|
|Perf|Only once, during deployment window|
|Prod|Only once, during deployment window|
