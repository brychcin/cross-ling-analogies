# Cross-lingual Word Analogies using Linear Transformations between Semantic Spaces

The ability to represent the meaning of words is one of the core parts of natural language understanding (NLU), with applications ranging across machine translation, summarization, question answering, information retrieval, etc. The need for reasoning in multilingual contexts and transferring knowledge in cross-lingual systems has given rise to cross-lingual semantic spaces, which learn representations of words across different languages.

With growing attention to cross-lingual representations, it has became crucial to investigate proper evaluation schemes. The word-analogy-based evaluation has been one of the most common tools to evaluate linguistic relationships (such as male-female relationships or verb tenses) encoded in monolingual meaning representations. In this paper, we go beyond monolingual representations and generalize the word analogy task across languages to provide a new intrinsic evaluation tool for cross-lingual semantic spaces. Our approach allows examining cross-lingual projections and their impact on different aspects of meaning. It helps to discover potential weaknesses or advantages of cross-lingual methods before they are incorporated into different intelligent systems.

We experiment with six languages within different language families, including English, German, Spanish, Italian, Czech, and Croatian. State-of-the-art monolingual semantic spaces are transformed into a shared space using dictionaries of word translations. We compare several linear transformations and rank them for experiments with monolingual (no transformation), bilingual (one semantic space is transformed to another), and multilingual (all semantic spaces are transformed onto English space) versions of semantic spaces. We show that tested linear transformations preserve relationships between words (word analogies) and lead to impressive results. We achieve average accuracy of 51.1%, 43.1%, and 38.2% for monolingual, bilingual, and multilingual semantic spaces, respectively.


## Reference

If you found this corpus useful, please cite the following paper:

Tomáš Brychcín, Stephen Taylor, Lukáš Svoboda. **"Cross-lingual Word Analogies using Linear Transformations between Semantic Spaces."** *Expert Systems with Applications*, 2019.

    @article{BRYCHCIN2019,
      title = "Cross-lingual Word Analogies using Linear Transformations between Semantic Spaces",
      journal = "Expert Systems with Applications",
      year = "2019",
      issn = "0957-4174",
      doi = "https://doi.org/10.1016/j.eswa.2019.06.021",
      url = "http://www.sciencedirect.com/science/article/pii/S0957417419304191",
      author = "Tom\'{a}\v{s} Brychc\'{i}n and Stephen Taylor and Luk\'{a}\v{s} Svoboda",
    }
