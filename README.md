### Hi there 👋!

- I'm Pascual Merita, currently pursuing a Master's in Artificial Intelligence at [The University of Edinburgh](https://www.ed.ac.uk/studying/postgraduate/degrees?id=107&r=site/view).

**Multimodal Dynamic Token Pooling in Transformers**
- Transformers are widely used in the AI space, but training them requires significant time and resources. Research in the text domain demonstrates that dynamic token pooling can increase training speeds by up to fivefold and significantly improve performance. My investigation extends this concept to other modalities, such as audio and vision, with the potential for even greater training speed gains – exceeding 10x.

**LLM Probing as a Method for Hallucination Detection**
- LLMs offer immense potential, but their tendency to ‘hallucinate’ misleading information poses serious risks, particularly in the medical field. Our research addresses this by training ML models (called probes) on LLM’s latent activations to detect hallucinations. Our findings show that this approach generalizes well to more difficult datasets, paving the way for more reliable AI in the future.

**Siamese Song2Vec**
- Major music streaming platforms employ advanced recommendation systems that carefully balance diversity and similarity to provide personalized song recommendations. However, DJs and music producers exhibit unique needs, requiring similarity-based recommendations. My study leverages the distributional hypothesis (coming from NLP) to generate unsupervised, similary-based song embeddings form playlists. We do so by employing Siamese Neural Network using Triplet Loss on song's Mel Spectograms.

**Improving audio-filtering music recommendation systems using deep learning methodologies**
- I tackle the same problem explained in the bullet point above but now from a different angle. My approach consists of the following two steps: First, upon receiving a user-inputted audio file, tags, such as instruments and genres, are extracted using a Convolutional Recurrent Neural Network. Songs that lack these tags are excluded from the pool of potential recommendations. Second, the audio file is processed through a Short-Chunk Convolutional Neural Network with Residual Connections. Medium-level features, including liveness and tempo, are extracted, and a similarity metric is employed to compare these features with the subset of songs from the first step. The result is a curated selection of similar songs


- 🌐 Interested in my work? Let's connect on [LinkedIn](https://www.linkedin.com/in/pascual-merita-torres-0098401ba/).




