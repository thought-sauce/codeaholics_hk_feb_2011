Mongo: Embed
-------------

###Pros
* Faster <div class="subtext">(if company in memory, employee also in memory)</div>
* Less index space

###Cons
* the single object can be too big <div class="subtext">(4MB limit)</div>
* complicated to run global queries on subdocument <div class="subtext">(i.e. use map reduce to grab employee)</div>