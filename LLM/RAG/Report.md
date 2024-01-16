# Objective 
The project's primary goal was to fine-tune a language model to emulate the poetic style of William Blake. By training the model on a curated collection of Blake's poems, the aim was to enable it to generate new poetry that aligns closely with Blake's thematic and stylistic characteristics. 

## Methodology 
Poet Selection: William Blake was chosen for his distinctive poetic style. Data Collection: 30-40 of Blake's poems were scraped and compiled into a single JSONL file, William_Blake.jsonl. 

- Model Selection: The Mistral 7B model was chosen, and configured for 4-bit quantization to enhance processing efficiency. 
- Tokenization and Dataset Preparation: Poems were tokenized using a custom tokenizer designed for compatibility with the model's architecture.
- Model Training: The Mistral 7B model underwent fine-tuning with the tokenized Blake poems dataset. 

## Experiments and Results 
Base Model Evaluation: Before fine-tuning, the base model generated Blake-style poems with varying degrees of success, some capturing the essence of Blake's themes and style. 
- Chunking Strategy Comparison: The [poem] and [line] chunking options were evaluated to determine their effectiveness in generating coherent language. The [poem] chunking was found to produce more coherent and stylistically consistent outputs. 
- Cosine Similarity Analysis: Generated poems were compared with the original Blake poems using cosine similarity. High similarity scores, particularly with "Auguries of Innocence," indicated the model’s success in capturing Blake's style. 
- Generated Poems Analysis: Five poems were generated post-training, revealing a significant improvement in coherence and stylistic alignment with Blake's work. 

## Key Findings 
- High Fidelity to Blake’s Style: The fine-tuned model effectively emulated Blake's unique poetic style, both in thematic depth and stylistic elements. 
- Optimal Chunking Approach: The [poem] chunking method was found to be superior in maintaining coherence and thematic continuity. 
- Quantitative Validation: The cosine similarity scores demonstrated a strong correlation between the model-generated poems and Blake's originals, particularly with "Auguries of Innocence," highlighting the model's nuanced understanding of Blake's work. 
- Qualitative Confirmation: Human assessment of the generated poems confirmed their resemblance to Blake's style, affirming the model’s effectiveness. 

## Conclusion 
This project successfully demonstrates the capacity of advanced language models to mimic the poetic style of a specific author, in this case, William Blake. The fine-tuned model displayed a remarkable ability to generate new poetry that resonated with Blake's thematic richness and stylistic idiosyncrasies. This achievement underscores the potential of AI in creative literary endeavors, presenting innovative avenues for exploring and expanding upon the literary legacies of historic poets. The model's proficiency in capturing Blake's complex thematic elements and stylistic nuances paves the way for future explorations in AI-assisted literary creation and analysis.

