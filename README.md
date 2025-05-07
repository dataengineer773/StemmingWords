We have tokenized words and want to convert them into their root forms, Use NLTK’s PorterStemmer, Stemming reduces a word to its stem by identifying and removing affixes (e.g., gerunds) while keeping
the root meaning of the word. For example, both “tradition” and “traditional” have “tradit” as their
stem, indicating that while they are different words they represent the same general concept. By
stemming our text data, we transform it to something less readable, but closer to its base meaning and
thus more suitable for comparison across observations. NLTK’s PorterStemmer implements the widely
used Porter stemming algorithm to remove or replace common suffixes to produce the word stem
