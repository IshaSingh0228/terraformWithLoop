# terraformWithLoop
Deploying aws resources using for_each construct

Points to Note
--------------
1.for_each supports sets and maps only when used on a resource. When for_each loops over a set, it makes each available vaule from set in each.value. It can also be available in each.key, though you typically use each.key only with maps of key-value pairs.
2. 
