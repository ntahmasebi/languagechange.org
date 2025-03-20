+++
# Project title.
title = "Wp1: Word Sense Induction"

# Date this page was created..
date = 2018-12-01T00:00:00

# Project summary to display on homepage.
summary = "Word Sense Induction (WSI) is the task of automatically finding the meaning of words from text. "

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Data Science", "Word Sense Induction", "Sense-differentiated embeddings", "WSI"]

# Optional external URL for project (replaces project detail page).
#external_link = "https://spraakbanken.gu.se/eng/culturomics"

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  #caption = "Photo by Toa Heftiba on Unsplash"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

Automatically derived word senses are the basis for our continued work. For English, evaluated methods (Pantel and Lin, 2002; Brody and Lapata, 2009; Lau et al., 2012) exist and new methods are developed, the latest is the utilization of word embeddings (Nieto Piña and Johansson, 2015; Trask et al., 2015; Pelevina et al., 2016; Li and Jurafsky, 2015). For Swedish, these methods have not been tested at large scale and might perform less well due to smaller amounts of available text. 
    
In our previous work, we performed small-scale evaluation of embedding-based methods and the curvature clustering method (Dorow et al., 2005) on our historical newspaper corpus Kubhist. Neither of these have proven very effective and it remains to investigate the reasons, e.g., corpora size, level of noise or differences in morphology and syntax. 

<h2 id="plan">The plan</h2>

We will adapt, develop and evaluate methods that are tailored to Swedish; and keep links to original contexts, hence providing evidence of each sense. Extracted senses can be linked to dictionaries to aid lexicographical work.    
	
<h2 id="references">References</h2>

S. Brody and M. Lapata. Bayesian word sense induction. In EACL, 2009  
B. Dorow, J.-p. Eckmann, and D. Sergi. Using curvature and markov clustering in graphs for lexical acquisition and word sense discrimination. In MEANING, 2005.  
J. H. Lau, P. Cook, D. McCarthy, D. Newman, and T. Baldwin. Word Sense Induction for Novel Sense Detection. In EACL, 2012  
J. Li and D. Jurafsky. Do multi-sense embeddings improve natural language understanding? In EMNLP, 2015.  
L. Nieto Piña and R. Johansson. A simple and efficient method to generate word sense representations. In RANLP, 2015.  
P. Pantel and D. Lin. Discovering word senses from text. In KDD, 2002.  
M. Pelevina, N. Arefyev, C. Biemann, and A. Panchenko. Making sense of word embeddings. In RepL4NLP, 2016.  
A. Trask, P. Michalak, and J. Liu. sense2vec - A fast and accurate method for word sense disambiguation in neural word embeddings. CoRR, abs/1511.06388, 2015.  

