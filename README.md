This is a frequency list of Vietnamese words. 

Every other frequency list currently available on the web was made by looking at groups of alphabetic characters split at `\b`, or "word boundaries", using the programming definition of a "word." 

However, in Vietnamese, spaces denote not only word boundaries, but also *syllable* boundaries—and a significant proportion of the Vietnamese lexicon consists of polysyllabic words.

This data is based on:

- **Leipzig Corpora Collection** (1M mixed-source Vietnamese sentences).  
  Source: Leipzig Wortschatz Project.
  Download: [Leipzig Wortschatz](https://wortschatz.uni-leipzig.de/en/download/)

- **OpenSubtitles2016 Vietnamese corpus**, originally described in:  
  Lison, P. & Tiedemann, J. (2016). *OpenSubtitles2016: Extracting Large Parallel Corpora from Movie and TV Subtitles.* Proceedings of LREC 2016.  
  I used the cleaned and compiled version available [here](https://github.com/sinhngn/English-Vietnamese-parallel-corpus-context.

Before word frequencies were calculated, both corpora were first combined and tokenized using `pyvi` ([GitHub](https://github.com/trungtv/pyvi)), and then words were normalized to account for orthographic differences (tone mark placement in ambiguous cases, differences in capitalization, and the use of final *i/y*). 