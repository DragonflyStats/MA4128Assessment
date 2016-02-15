Analysing Twitter Data with Neo4j
======================================

Neo4j is an open-source graph database implemented in Java and accessible from software written in other languages using the Cypher Query Language through a transactional HTTP endpoint. It is a ver popular graph database. It has been described an ACID-compliant transactional database with native graph storage and processing. Neo4j was orgially released in February, 2010, and the company ia based in the San Francisco Bay Area, US and Malmö, Sweden.

There are many uses of Neo4j, and graph databases in general. I will now discuss several applications of using graph databases, specifically Neo4j, in order to analyse and store data and the benefits and cons of doing so.

** Master Data Management **
The world of master data is changing. Data architects and application developers are swapping their relational databases with graph databases to store their master data. This switch enables them to use a data store optimized to discover new insights in existing data, provide a 360-degree view of master data and answer questions about data relationships in real time. Business gain the benefit of real time insights into data, along with a place to store and model their data. Some challenges that can stem from this, however, are:
* **Complex and Hierarchical Datasets** are quite difficult to manage in this state. The code is difficult to build, slow to run and expensive and time-consuming to maintain.
* **Real-time Query Performance** Master data systems must integrate with and provide data to a host of applications within the business – often in real time. However, traversing a complex and highly interconnected data set to provide real-time information is a challenge, and often leads to slow responses if the data is quite large.
* **Dynamic Structure** Master data is highly dynamic with constant addition and re-organization of nodes, making it harder for your developers to design systems that accommodate both current and future requirements. This is due to the changing nature.

Where Neo4j comes in, is here. The problem with relational database management systems is that they are no longer as efficient or useful for storing master data. Neo4j uses native graph storing, meaning,  it stores interconnected master data that is neither linear nor purely hierarchical. Due to this method of storing, indexing is not forced either, making accessing the data easier too.

** Fraud Detection **
Neo4j presents a new, and interesting, way to detect fraud. As fraudsters get more sophisticated, organizations are augmenting their fraud detection capabilities to uncover fraud rings and other sophisticated scams with precision and in real time. Whether it’s first-party bank fraud, money laundering, insurance fraud or e-commerce fraud. While no fraud prevention measures are perfect, but by looking beyond individual data points to the connections that link them, your efforts significantly improve. Neo4j uncovers difficult-to-detect patterns that far outstrip traditional representations such as tables. An increasing number of companies use Neo4j as the database of choice for their fraud detection and anti-money laundering applications.

#### references:
http://www.sandtable.com/analysing-twitter-data-with-neo4j-2/
http://neo4j.com/use-cases/