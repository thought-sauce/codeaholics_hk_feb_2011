Mongo: Embed vs Relational
-------------

###Embed (de-normalized)

<pre><code>
company model:
{
  _id: "897132", name: "Thought Sauce", 
  employee: {_id: "12345", name: "Eddie" }
}
</code></pre>

###Relational (normalized)

<pre><code>
company model:
{
  _id: "897132", name: "Thought Sauce"
}
</code></pre>
<pre><code>
employee model:
{
  _id: "12345", name: "Eddie", company_id: "897132" 
}
</code></pre>