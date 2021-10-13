# Knowledge_Graph_UBT_Entities
This Repo consists of a Knowledge Graph build upon entities of the university of bayreuth for the seminar "Data Mining im Marketing mit R". The knowledge graph is used as the foundation for a question answer system that lets the user retrieve information about the university such as "What's for lunch at the canteen today?".

# How it works
We build a Web Scraper to scrape different websites of the university of bayreuth, such as the the individual chair sites or the canteen page. Data is collected and stored in a format, that resembles a knowledge graph.
The user can pose a question, which is then disassembled for the source node, the target node and the required relation. By querying the knowledge graph in such a way, an answer can be retrieved. We used techniques such as word embeddings
to check for synonymous relations.

# Results
A demo for the script is shown below:



![alt text](https://github.com/schmid-sebastian/Knowledge_Graph_UBT_Entities/blob/master/demo.gif?raw=true)

The script was deployed on an Amazon AWS server, which was online for a month. We send the URL to other students, to collect their queries and debug the code. The resulting website for three different queries looked like this:


![alt text](https://github.com/schmid-sebastian/Knowledge_Graph_UBT_Entities/blob/master/website1.jpg?raw=true)

![alt text](https://github.com/schmid-sebastian/Knowledge_Graph_UBT_Entities/blob/master/website2.jpg?raw=true)

![alt text](https://github.com/schmid-sebastian/Knowledge_Graph_UBT_Entities/blob/master/website3.jpg?raw=true)
