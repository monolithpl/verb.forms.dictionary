# Verb Forms Dictionary
The most comprehensive dictionary of English verb forms online today, combining data from:
 * British and American verb forms in [Oxford Advanced Learner's Dictionary 9th edition](http://www.oxfordlearnersdictionaries.com/)
 * British and American verb forms in [Longman Dictionary of Contemporary English 6th edition](http://www.ldoceonline.com/)
 * unverified verb forms from [Python NLP Research](https://github.com/simonhughes22/PythonNlpResearch)

## demo

##data format
- csv / excel format in ```csv``` folder
- json format in ```json``` folder
- packed trie format in ```packedtrie``` folder

Additionally, three sets of the Verb Forms Dictinary are available:
- ```verbs-dictionaries``` - authoritative, human compiled list of verbs and their verb forms
- ```verbs-automatic``` - unverified list of verbs from Python NLP Research (may contain errors, non-verbs or even non-words)
- ```verbs-all``` - the two above lists combined

###file format
|Verb - Base form / Infinitive / Present Simple / 1st Person | Present Simple / 3rd Person | Past Simple | Past Participle | Present Participle (-ing)|
|-------|---------------|------------|-------|-----|
|_(I / you / we / they)_ | _(he / she / it)_ | _(all)_ | _(all)_ | _(all)_|
|abstract|abstracts|abstracted|abstracted|abstracting|
|begin|begins|began|begun|beginning|
|burn|burns|burned|burned|burning|
|burn|burns|burnt|burnt|burning|

## example usage
Below are some projects that make use of the word associations dictionary:
- [Verb Finder](https://github.com/monolithpl/verb-finder)

MIT License

Copyright 2016 Wiktor Jakubczyc
