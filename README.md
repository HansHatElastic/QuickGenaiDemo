# QuickGenaiDemo
 This is for setting up an index template plus pipeliness for rapid manual loading some docs for the playground using the E5 model. Code is derived from a web crawler.
 
Note that only the "body_content" from the input doc is picked up for inference !

Objective: if you need some data for the playground demo, and for reasons the source docs are hard to get or crawl you can add manually a small set of docs. This is not "best practices production code"

Steps:
- Use the API calls from the txt docs
Console
PUT mysearch-<name of your index>
POST mysearch-<name of your index>/_doc
{ "body_content" : "Hello world , this is my first doc for the playground"
}
 
