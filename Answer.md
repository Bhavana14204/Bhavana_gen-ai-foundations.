Question 1: The Vector Conflict

The similarity score may show that the two sentences are similar because both contain the word "light". However, the meanings of "light" are completely different in the two sentences. A Bag-of-Words model only counts words and does not understand their meaning. Therefore, it creates a false similarity between sentences that actually talk about different things.

Question 2: The Context Blindspot

The Bag-of-Words approach cannot understand the context of a sentence. It only looks at how many times words appear and ignores their meaning and position. Because of this, search engines and chatbots may give incorrect results when a word has multiple meanings. The most important thing lost is the context and actual meaning of words.

Question 3: The GenAI Architectural Fix

Modern AI models like GPT and LLaMA understand words based on the surrounding words in a sentence. They use Self-Attention to focus on the context and Context-Aware Embeddings to create different vector representations for the same word in different situations. For example, the word "light" will have one meaning when talking about healthy food and a different meaning when talking about brightness. This helps AI understand language much more accurately.
