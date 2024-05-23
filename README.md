### Hi there 👋

I'm **Pascual Merita**, currently pursuing a Master's in Artificial Intelligence at [The University of Edinburgh](https://www.ed.ac.uk/studying/postgraduate/degrees?id=107&r=site/view).

---

<details>
<summary><strong>Project Highlights</strong></summary>
<br>

> #### **AMP: Adaptive Merging and Pruning in Vision Transformers (2024 - Private Repository)**
> - *Transformers have revolutionized fields like natural language processing and computer vision due to their scalability and effectiveness in utilizing GPUs for large datasets. However, their utility is hampered by a quadratic computational complexity with respect to sequence length, posing significant challenges in high resolution image processing. While recent strategies have attempted to address this by pruning or merging sequence tokens progressively, these methods rely on fixed per-layer ratios that do not adjust to the specifics of the processed image. Our proposed method circumvents the need for such predetermined hyperparameters by enabling the network to autonomously determine optimal ratios tailored to each input. This adaptability is facilitated through a multi-layer perceptron that generates a differentiable mask, simulating the pruning process. Additionally, cross-attention between the masked and original sequences simulates merging. Although our approach does not enhance training efficiency, it significantly boosts inference speed in image classification tasks.

> ---

> #### **LLM Probing as a Method for Hallucination Detection (2024 - Private Repository)**
> - *LLMs* offer immense potential, but their tendency to ‘hallucinate’ misleading information poses serious risks, particularly in the medical field. Our research addresses this by training ML models (called *probes*) on LLM’s latent activations to detect hallucinations. Our findings show that this approach generalizes well to more difficult datasets, paving the way for more reliable AI in the future.

> ---
 
> #### **Siamese Song2Vec (2024 - Private Repository)**
> - Major music streaming platforms employ advanced recommendation systems that carefully balance diversity and similarity to provide personalized song recommendations. However, DJs and music producers exhibit unique needs, requiring similarity-based recommendations. My study leverages the distributional hypothesis (coming from NLP) to generate unsupervised, similarity-based song embeddings from playlists. We do so by employing *Siamese Neural Networks* using Triplet Loss on song's Mel Spectograms.

> ---

> #### **Improving Audio-Filtering Music Recommendation Systems Using Deep Learning Methodologies (2023 - [Public Repo](https://github.com/PascualMeritaTorres/Deep-Learning-Music-Recommendation-System))**
> - I tackle the same problem explained in the bullet point above but now from a different angle. My approach consists of the following two steps: First, upon receiving a user-inputted audio file, tags, such as instruments and genres, are extracted using a *Convolutional Recurrent Neural Network*. Songs that lack these tags are excluded from the pool of potential recommendations. Second, the audio file is processed through a *Short-Chunk Convolutional Neural Network with Residual Connections*. Medium-level features, including liveness and tempo, are extracted, and a similarity metric is employed to compare these features with the subset of songs from the first step. The result is a curated selection of similar songs.

</details>

---
