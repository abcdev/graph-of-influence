# Graph of influence

Inspired by [Tony Hirsts blogpost](https://blog.ouseful.info/2012/07/03/visualising-related-entries-in-wikipedia-using-gephi/) this graph resembles the ontology connection "influencedBy" of DBpedia.org for a large amount of people, groups and movements. It's a good starting point to get an overview of the influences a certain entity contains. Be aware that this is western-centric. 

![Preview image of graph](preview.png)

There is one preprocessed .gephi file that has been laid out with the [Gephi graph application](https://gephi.org/). If it gets to messy you can filter the shown nodes. Node size ranking should also be applied.

To start from scratch simply use the raw_graph.dot contents in your favorite graph layout program (e.g. Gephi).

The following DBpedia entries are included:

- Linguist

- Scientist
- Psychologist
- Philosopher
- Writer
- MemberResistanceMovement
- MilitaryPerson
- Politician
- Economist
- Artist
- ontology/philosophicalSchool
- ontology/movement
- ontology/party
- property/schoolTradition
- ontology/movement

### License

This work is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License)