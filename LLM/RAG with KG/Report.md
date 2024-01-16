# Objective
The primary aim was to construct and analyze Knowledge Graphs (KG) derived from William Blake's poetry and related historical articles, focusing on their structure, content, and thematic interconnections. 

## Methodology 
Data Preparation:
- Poems by William Blake and articles on pertinent historical events were selected.
- Texts were processed using Spacy's en_core_web_sm pipeline, facilitating natural language processing and analysis. 

Knowledge Graph Construction: 
- Employed Textacy for Subject-Verb-Object (SVO) extraction from Blake's texts and related articles.
- Generated nodes and relations for the KGs based on the extracted SVO triples.
- Created Directed Graphs (DiGraph) using NetworkX for both poem and article texts.
- Nodes represented entities or concepts, while edges represented their relational actions or interactions. 

Graph Visualization: 
- Utilized matplotlib and NetworkX to visualize the KGs, providing a graphical representation of the thematic and relational structures within the texts.
- Edge labels indicated the nature of the actions connecting the nodes. 

## Experiments and Results 
KG for Poem: 
- Nodes: Entities like 'I', 'joy', 'day', 'year', 'sit', 'hour', etc., were extracted from the poem.
- Relations: Actions like 'love', 'drives', 'spend', 'can_take', etc., were used to connect the nodes, depicting the poem's thematic and narrative structure.
- Visualization: The graph showed a complex web of interactions, illuminating the poem’s thematic depth and structure. 

KG for Article: 
- Similar to the poem KG, but derived from a historical article, providing a visual representation of the article's thematic elements and their interconnections. 

Topic Modeling: 
- Applied LDA topic modeling to the articles, identifying major themes like land, tenants, acts, and Inclosure.
- These themes informed the construction of micro KGs, further dissecting the thematic elements. 

## Key Findings 
Thematic Interconnection: 
- The KGs revealed a deep interplay of themes and concepts within and between Blake's poetry and the historical context.
- The poem KG captured the emotional and philosophical nuances, while the article KG provided a factual, historical perspective. 

Insightful Visualizations: 
- The graphs provided an intuitive visual understanding of complex thematic structures, making abstract concepts more tangible. 

Comparative Analysis: 
- By comparing the poem and article KGs, similarities and differences in thematic elements and narrative structures were identified.
- This comparison allowed for a nuanced understanding of how Blake’s poetry might reflect or diverge from the contemporaneous historical narrative. 

Topic-Specific Graphs: 
- The micro KGs based on LDA topic modeling offered focused insights into specific themes, adding depth to the overall analysis. 

## Conclusion 
The construction and analysis of Knowledge Graphs from William Blake's poetry and related historical articles provided a novel approach to literary analysis. The KGs elucidated thematic interconnections, narrative structures, and the poet's engagement with contemporary events. This method proved valuable in uncovering the subtle interplay between literary works and their historical context, offering insights that traditional textual analysis might overlook. The visual aspect of KGs added an intuitive dimension to understanding complex literary and historical relationships. This project underscores the potential of KGs in enhancing literary studies, particularly in exploring the connections between literature and historical contexts. 

