Json Compare
============

`json-compare` is a library to compare JSON structures, and currently in one specific way. It can check whether a JSON value is a proper subset of another JSON value. This can be useful in an API, where some resource emit a partial JSON structure that should be a subset of a more detailed JSON structure. For example, you can use this to verify that the JSON you get for a single user in the `/users` resource is a subset of the detailed JSON you get from the `/users/{uid}` resource.  
