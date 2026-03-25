This section is concerned with the stimulus selection for lexicon decision tasks. Items are generally selected to fit specific criteria that depend on the research question. The first step is to select the items – to identify suitable words and find or generate pseudowords. We will specifically focus on the selection of words and pseudowords in German.


## Where to Find Words
One should select words from corpora. The field of corpus linguistics provides text resources that offer representative collections of texts, including the most critical words from a given language. These resources allow us to determine the word status of a letter string and word characteristics that are important as selection criteria. For example, word frequency is one of the essential variables for lexical decision studies, that describes how often a word occurs in a corpus which, depending on the corpus quality (i.e., size and register), more or less reflects the frequency in natural language ([more details](https://doi.org/10.1177/0963721417727521)). 


### Corpora to Consider
Conducting a lexical decision experiment in German requires relying on existing resources. Many resources are freely available, and others require a university account or subscription. Generally, corpora differ in size and register. A small corpus may provide inaccurate frequency estimates, especially for low-frequency words ([more details](https://doi.org/10.1037/0096-3445.113.2.256)). Register refers to the population sampled in the corpus. For example, the words in a child-book corpus differ from those in an adult newspaper corpus. Further, we can distinguish between written, spoken, subtitle and internet corpora as well as ways to generate specific corpora. Below, we present a non-exhaustive list of German resources that the members of the TRUST group recommend. To ensure word status, we highly recommended checking multiple corpora to account for potential misspellings that happen regularly. 


We provide links in the following.

Register Legend:

| Symbol | Register |
| --- | --- |
| 👧 | Children |

Note that no symbol reflects that the register are typical adults.

#### Written Corpora 
Texts collected from newspapers and books. 

- [dlexDB corpus](https://doi.org/10.5281/zenodo.15097663)
    - Syllable frequency, letter n-gram frequencies, and orthographic similarity
- [DWDS corpus](https://www.dwds.de/r/lexdb#kern)
    - Provides annotated data, representative for 20th century
- [WebCELEX corpus](https://webcelex.ivdnt.org/) (University-Login needed)
    - Easy to use, contains frequency values, lemmatisation, phonological transcription and syllable-level statistics; based only on newspapers, so not representative 
- 👧[ChildLex corpus](https://www.dwds.de/d/korpora/childlex)
    - Separate frequency counts for different ages (between 6 and 12); contains annotation about word class, lemma, orthographic neighbourhood, bigram frequencies, etc.


#### Spoken Corpora 
[Here](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.sys_inv?v_session_id=) one can find a list of German corpora of spoken language with diverse registers and sizes (sign up necessary) constantly updated by the Institute of the German Language in Mannheim. 

#### Subtitle Corpora 
Texts that have been used as movie/TV series subtitles. They represent spoken language after a script but provide written word forms. One advantage of these is that they exist not only for German but also other languages.

- [SubtLex corpus](https://osf.io/py9ba/)
- [FILMS corpus](https://osf.io/rd7p6/)

#### Internet Corpora 
This type of resource collects texts available on the Internet. The advantage is that a large amount of text is available. However, data quality is typically lower (i.e., there is a higher rate of misspellings).

- [Leipzig corpus](https://corpora.uni-leipzig.de/en?corpusId=deu_news_2021) 
- [deWaC corpus](https://wacky.sslmit.unibo.it/doku.php?id=frequency_lists)

#### Ways to Generate Corpora 
Here are new ideas for creating corpora with generative language models ([more details](https://doi.org/10.31234/osf.io/gm9b6_v5)). 

- 👧[LLM created ChildLex corpora](https://doi.org/10.17605/OSF.IO/WMUVJ)

### Variables to Consider 

Words vary in terms of orthographic features (e.g., number of letters, written word form frequency), phonological features (e.g., number of syllables, number of phonemes), morphological features (e.g., morphological complexity, number of morphemes), syntactical features (e.g., part of speech) and semantic features (e.g., word class, valence). There are no strict rules for which items to exclude when selecting words/pseudowords for a study. Manual filtering is not recommended, as it is time-consuming and error-prone. The filtering process depends on the research question. To stay closer to actual use of language and control for spelling errors, one can select words from a dictionary instead of a corpus or use it for additional filtering.  

#### Exclusion of Taboo Words ![Importance Rating 2](images/rating2.png)
Some studies exclude taboo words, which has both advantages and disadvantages. If unsure about the ethical use of swearwords, it is advised to consult with an ethics committee. As swearwords are part of everyday human language, there may be theoretical reasons for being specifically interested in these items. Unless required by the research questions, we recommended excluding slurs that some participants may perceive to be personally offensive and to include a trigger warning if such words are under investigation. [Sulpizio et al. (2024)](https://doi.org/10.3758/s13428-024-02376-6) provide a full list of German taboo words as supplementary materials.

#### Inflections
German is an especially inflection-rich language and has more inflected words than English. Inflected word forms are adjustments to base word forms that indicate grammatical aspects such as time or gender. The experimenter needs to decide how to treat inflected word forms. For example, the verb "gehen" ("to go") has 17 different forms (e.g., "ging" (past form)).

- There are many more inflected word forms than lemmas, including very similar words that are almost identical in both form and meaning (e.g., "Katze" – cat, and "Katzen"). If inflected word forms are included, one may want to ensure that there are not too many similar words in the chosen word set.
- Gender-Forms: Some nouns have gendered forms (Lehrer vs. Lehrerin). Traditionally, the male form is considered the default in most cases. It is possible to include only the more frequent form of each word. However, this may provide a biased picture, especially across multiple studies or in a large-scale study. In attempts to make language more gender-neutral, non-gendered plural forms are also increasingly common. These may be typographically unusual, such as the intrusion of non-letter characters "Lehrer*innen", "Lehrer:innen", or "Lehrer_innen". Other forms can be camel-back letters ("LehrerInnen") or intermediate slashes ("Lehrer/innen"). Note that these gendered forms may be perceived as exclusive of non-binary individuals. If gendered forms with unusual typographic characteristics are included, there must be foil non-words with similar structures to avoid providing a non-lexical cue to the word's lexicality. One option could be using 50% of the relevant words in female form and the other 50% in male form. This will result in an equal representation of male and female versions, but not considering non-binary individuals. Accounting for the non-binary version, one could use gender neutral forms like "Lerhrerperson".
- Using inflected words is closer to the actual use of language

####  Inclusion of Compounds
A specialty of German is the use of compound words (e.g., “Kühlschrank”, which means fridge, is a cooling cupboard when translated literally). The creation of compound words is productive, such that speakers can create novel word forms on the fly. This poses some questions when selecting items. 

- Including compounds allows us to examine a feature for which the German language is famous, and it stays closer to the actual use of language.  
- If compounds are included, one might need a much larger number of items to have a broad coverage of representative words. At the same time, a larger number of words becomes available. 
- The frequency counts for compound words may not be comparable cross-linguistically. At the extreme end, we may have perfectly legal and understandable neologisms with a frequency of 0. This is also to be considered when applying a word frequency threshold. A potential solution here is to consider a combined version of the single-word frequency within the individual compounds.

#### Part of Speech
Excluding certain parts of speech (e.g., function words) can simplify the selection process. However, it may also reduce the language's representativeness.

#### Lemmatization
Lemmatization involves using lemmas (i.e., base forms of words; typically found in dictionaries) instead of individual word forms. 

Pros:

- Shorter list of words
- Lemmas have more overlap with other corpora
- Making inferences about a type based on the lemma RT is better than not having an RT of the type
- Many more practical applications of RT data with lemmas (e.g., evaluating text difficulty, predicting item difficulty)

Cons:

- Lemmas are often not identical to what is seen or heard in natural language

####  Filtering by other word characteristics
It is common to filter experimental items by other word characteristics. This has the advantage of removing “weird” items and removing variance that is not associated with an effect of interest, but at the same time runs the risk of creating a word set that is not representative of the actual language. 

Pro

- Reduces the number of untypical words (i.e., too long, too seldom, too untypical letter combinations)

Cons

- May not be representative of the language
- The cut-off points will be somewhat arbitrary 

##### Word frequency 
There is an argument for excluding words with particularly low frequency, as these will be unknown to many participants.  

- The experimenter can base the cut-off on written or spoken word frequency. Although they correlate, there is some dissociation between them. 
- One should expect higher error rates if many low-frequency words are included. Rarely used words will likely be categorised as "not-a-word". 
- It may be advisable to select the words so that one can check if the frequency effect is present in the collected data. This will provide a sanity check. The frequency effect is generally observable when the frequency lies between 0 and 2, in log-frequency per million.

##### Word length (letters, phonemes, syllables) 

- There may be pragmatic reasons for excluding very long words (i.e., making sure they fit on the screen)
- There may be physiological reasons for excluding very long words (i.e., making sure the word fits the size of the retina, thus restricting the need for eye movements; an Empirical length restriction estimate would be 7 or fewer letters (e.g., see [Kliegl et al., 2004](https://doi.org/10.1080/09541440340000213)).
- One should be mindful that this may lead to a non-representative sample of words, such as a disproportionate exclusion of compound words and low-frequency words. 
- Furthermore, there is no agreed-upon cut-off at which one would exclude words. 
- Length covaries with many other variables, such as orthographic neighbourhood (long words have very few orthographic neighbours, if any). In selecting the length range, one should consider the extent to which length covaries with variables one is interested in.
- An option taken by some previous studies (e.g., [Andrews, 1989](https://doi.org/10.1037/0278-7393.15.5.802) or [Fu & Gagl, 2025](https://doi.org/10.1162/jocn_a_02301)) is to restrict the items to one word length, e.g., using only monosyllabic four-letter words, to minimise potential sources of variability when interested in a specific effect.

##### Orthographic similarity/familiarity 

- There are many ways to measure orthographic similarity/familiarity of a word and non-words in contrast to an assumption of a memory storing lexcial itmes (i.e., learned words)
- Classical measures of letter string familiarity would be bi-, tri- or quadri-gram frequency measures that capture the familiarity of the substrings of any letter string.
- Classical measures of letter string similarity would be orthographic neighborhood size (i.e., there is also a phoneme level version), orthographic Levenshtein distance or similar. 
- More recently, neuro-cognitively motivated measures as the orthographic prediction error representations have been established, with a central advantage as the measure similarity without a confound in familiarity. 

## Non-word creation and selection:
A lexical decision task requires using non-word stimuli, most prominently pronounceable non-words, so-called pseudowords, or unpronounceable non-words, such as consonant strings. While they are often used simply as foils, interesting research questions can be addressed by manipulating non-word characteristics. In addition, non-word characteristics will influence task difficulty (e.g., see Fig. 1 in [Balota & Chumbley, 1984](https://doi.org/10.1037/0096-1523.10.3.340)). For example, the task difficulty will be high if pronouceable, very word-like pseudowords are used as foils only, as they do not provide non-lexical cues that participants can use to make a lexical decision. In contrast, when using consonant strings as foils, participants can rely only on a vowel detection strategy to solve the task, so task difficulty will be low. With increased task difficulty, deeper processing (e.g., semantic, phonological processing) is required, which is mostly desirable to detect any effects related to lexical processing. Thus, typically, non-words are word-like and comparable to the words used in the actual study in terms of orthographic similarity and familiarity. 

### Variables to consider for non-words
There are numerous variables for which words and non-words in an experiment can be used to consider Wordlikeness. If non-words are very non-word-like (e.g., "XQRPT"), the task will be easy for the participants to make correct lexical decisions without lexically processing the word. There are different ways to quantify word-likeness, and they are likely to be correlated. When available, it is advisable to check for all of the measures. 

- Consonant-vowel structure: Non-words that contain unusual consonant or vowel clusters should be avoided. One way to do this is to ensure that the CV structure is identical to the words used in the experiment.
- N-gram frequency: The inclusion of (many) rare letters (e.g., "Q", "X") will make non- less word-like. The same goes for multi-letter clusters such as bigrams or trigrams (e.g., the bigram "XQ" or trigram "XQA"). Information about n-gram frequency can be obtained from WordGen ([Duyck et al., 2004](https://doi.org/10.3758/BF03195595)). 
- Orthographic Levenshtein Distance (OLD) 20 ([Yarkoni et al., 2008](https://doi.org/10.3758/PBR.15.5.971))
- Morphological complexity: The morphological structure of words should match that of the words in the experiment.
- Visual-Orthographic characteristics like the orthographic prediction error ([Gagl et al., 2020](https://doi.org/10.1016/j.neuroimage.2020.116727), [Fu & Gagl, 2025](https://doi.org/10.1162/jocn_a_02301)) or Optimal Transport measures ([Taylor et al., 2025](http://doi.org/10.1101/2024.11.11.622929))

### How to create non-words
We recommend automating the process of non-word creation, especially if a large number of items are involved. There are numerous ways of doing this:

- Non-word creators for German are available, such as [Wuggy](https://doi.org/10.3758/BRM.42.3.627) or [UniPseudo](https://journals.sagepub.com/doi/abs/10.1177/17470218231164373). 
- Python is good for working with letter strings, and with medium-low programming skills, you can use it to create non-words:
    - Change one vowel: This is an easy way to create a non-word, but may result in a non-word that is highly similar to its baseword and will lead to increased lexical activation.
    - Exchange all vowels with consonants to a set of non-words that match the words in your experimental task. NOTE XENIA: I'M NOT SURE WHAT IS MEANT HERE
    - From your basewords, exchange consonants for consonants and vowels for vowels with a certain probability
    - From your basewords, exchanging bigrams or trigrams
    - Instead of relying on basewords, you can depend on language statistics: Combine common bigrams from the language (e.g., based on the FILMS corpus). Specify the length of your desired non-words. Select a random letter and then add letters with probabilities matching the structure of the German language. 

### What to avoid
- As for words, non-words similar to slurs that may cause offense may need to be avoided.
- If non-words should be pronounceable (i.e., pseudowords), one should eliminate illegal letter clusters. 
- Slang words and dialect: It is advisable to get a representative of your target population (e.g., teenagers, undergraduate students) to check for potential slang words.
- Items that are words in a language commonly spoken as a foreign language, such as English, French, or Italian.

## How to determine the effect of a specific variable based on lexical decision data
If we are interested in the effect of a given variable, we have several different paradigms available:

- Orthogonal design: Select words and non-words so they vary maximally on the variable of interest while keeping the conditions comparable to all other variables listed above. Although it’s sometimes unavoidable to use such a design, there are some disadvantages:
    - It often constrains the number of possible items, leading to small numbers.
    - The selection of items that are not representative of the language or orthography. 
    - Lack of methods to test if conditions are comparable (i.e., “matched”). Often, people use a t-test to show that, e.g., the two conditions don’t differ in word frequency, but this method has many problems. So we would advise against an orthogonal design.  

- Dichotomising of naturally continuous variables: If our variable of interest is continuous, we must make arbitrary decisions about what constitutes a “low” versus “high” value for assigning words to different conditions. This also prevents us from investigating non-linearity.
- Decorrelated itemsets: You can select a number of items that vary on your variable of interest but have a small correlation with other variables ([Protopapas & Kapnoula, 2013](https://escholarship.org/uc/item/1f2883gp)). The advantages are the same as above, except for the last point. 
- Large-scale study & bootstrapping ([Perry, 2022](https://doi.org/10.1177/17470218221086533)). 	
- Regression analysis: This involves using confounding variables as regressors of no interest. Here, statistical methods like linear mixed effect models are advised as they can account for variance components on the level of the stimuli and participants simultaneously. 

## Dialectic-specific considerations
The German language has a wide range of dialects. However, as most people (predominantly undergraduate students) are exposed to Standard German regularly (e.g., at school, through movies and TV), and due to the high mobility within the German-speaking realm (especially among undergraduate students), we don’t recommend overthinking this in the context of a lexical decision task.
