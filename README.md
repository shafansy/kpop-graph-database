# K-Pop Knowledge Graph
## Project Overview
This project implements a **K-Pop Knowledge Graph** using **Neo4j** to represent and explore relationships between K-Pop artists, agencies, albums, songs, genres, fandoms, and debut years.
The project applies graph database concepts to organize interconnected K-Pop data and uses **Cypher Query Language** to create, manage, query, and analyze the graph.
Through this project, K-Pop data is represented as interconnected nodes and relationships, allowing information to be explored through graph traversal and analytical queries.

## Objectives
- Build a graph database to represent interconnected K-Pop entities.
- Model relationships between artists, agencies, albums, songs, genres, fandoms, and debut years.
- Implement the database using Neo4j and Cypher.
- Apply constraints and indexes to support data consistency and efficient querying.
- Perform analytical queries to identify patterns within the dataset.

## Dataset
The dataset consists of selected K-Pop artists and their related information, including:
- Artist
- Agency
- Album
- Song
- Genre
- Fandom
- Debut Year

The dataset contains **30 selected artists**, consisting of both groups and solo artists.
Each artist is connected to related entities such as their entertainment agency, released album, performed song, fandom, and debut year. Songs are also connected to their respective genres.

## Key Insight
### Agency Distribution
- The agency analysis shows that SM Entertainment has the highest representation in the dataset, followed by JYP Entertainment and YG Entertainment.
- The three agencies have a relatively high representation among the selected artists in the dataset.
(This result reflects the composition of the project dataset and does not represent the overall distribution of artists across the entire K-Pop industry).

### Song Genre Distribution
- The genre analysis shows that Dance-pop is one of the most frequently represented genres in the dataset.
- Other frequently occurring genres include R&B and Pop/Dance, indicating that pop-oriented genres have a strong presence among the selected songs.
(The result represents genre frequency within the project dataset rather than overall popularity among K-Pop listeners).

### Artist Debut Trend
- The debut-year analysis shows relatively few debut records during the earlier years represented in the dataset.
- The number of debut records increases during the 2012–2015 period, with 2015 showing the highest number of debut records within the dataset.
(The dataset also includes artists who debuted in later years, with the latest represented debut year being 2022).

## Project Outcomes
This project demonstrates the implementation of a knowledge graph using Neo4j to model interconnected K-Pop data.
The project covers:

- Graph data modeling
- Node creation
- Relationship modeling
- Database constraints
- Indexing
- Cypher querying
- Graph-based data exploration
- Analytical querying
- Insight generation
The resulting knowledge graph provides a structured way to explore relationships between K-Pop artists and their associated entities.
