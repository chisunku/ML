# Objective 
The objective of this experiment is to investigate the effects of Parts of Speech (POS) substitutions in the poems of William Blake and Robert Frost, and use NLP techniques to understand how these linguistic changes affect the poems' semantic structure and reader interpretation. 

## Methodology 
Poet and Poem Selection: 
- Choose 20 representative poems from each poet.
- Utilized Python's BeautifulSoup for precise scraping, ensuring the retention of poetic structure and format. 

Data Scraping: Utilizing Python's BeautifulSoup library, we scraped poems from websites like allpoetry.com. This process involved handling various HTML structures to extract clean poetic text.

POS Tagging and Semantic Substitution Process: 
- Deployed spaCy for accurate POS tagging, crucial for identifying the linguistic structure of each poem.
- Created an algorithm for semantic substitutions, carefully selecting POS from one poet's work to replace in another's while maintaining semantic integrity. 

## Data Structure and Storage 
Each poem's data, including POS tags and the text, was meticulously organized into a JSON format. This structured data was then stored in a shared drive, facilitating easy access and manipulation for further analysis. 

## Experiments and Results 
POS Substitution Analysis: 
- In-depth substitutions were made, such as altering "worm" to "unknown worm" in Blake's "The Sick Rose," adding a layer of ambiguity.
- This substitution nuanced the poem’s theme of hidden corruption, subtly shifting its interpretative potential. 

Semantic Similarity and Coherence Analysis: 
- Utilized cosine similarity for quantitative assessment. For example, Blake's "The Sick Rose" displayed a marginal decrease in similarity 
post-substitution (from 0.3649 to 0.3477), indicating a slight shift in semantic content.
- This analysis helped quantify the impact of POS changes on the poems' overall semantic structure. 

Advanced Text Summarization and Topic Modeling: 
- Performed summarization to distill the essence of both original and transformed poems. The summaries revealed that while surface details changed, the core themes remained identifiable.
- Topic modeling via LDA and BERTopic highlighted consistent themes such as nature, love, and mortality, despite POS alterations. 

Statistical Insights and Comparative Study: 
- Compiled statistics offered a clear view of the linguistic changes. For instance, the change in the number of nouns and verbs in Frost's "Fire and Ice" from 11 to 10 and 10 to 9 respectively, subtly altered its rhythmic quality.
- Comparative analysis of original and transposed POS provided a clear lens to assess how specific changes impacted the poems' texture and tone.

## Results and Analysis 
We observed that POS substitutions had varied effects on the poems’ readability and thematic expression. While some substitutions preserved the original tone, others introduced intriguing new interpretations. 

## Conclusion 
The in-depth analysis of Parts of Speech (POS) substitutions in the works of William Blake and Robert Frost using NLP techniques revealed significant insights into how subtle linguistic changes can profoundly affect poetic interpretation. For instance, modifying a single word like "worm" to "unknown worm" in Blake's "The Sick Rose" introduced a deeper level of ambiguity and complexity, demonstrating the powerful role of word choice in shaping a poem's meaning and emotional impact. This project highlighted not only the delicate interplay between language and literary expression but also the effectiveness of NLP in uncovering nuanced interpretations of classical poetry. 
Furthermore, the quantitative assessment using cosine similarity provided a valuable metric for gauging the semantic shifts resulting from POS substitutions. Despite these linguistic alterations, the core themes of nature, mortality, and human experience remained strikingly resilient in both the original and transformed texts. This resilience, as evidenced through topic modeling and text summarization, underscores the enduring power of thematic elements in poetry. This experiment thus offered a compelling example of how NLP can be utilized to deepen our understanding and appreciation of literary art, reaffirming the intricate bond between language and poetic creativity. 
