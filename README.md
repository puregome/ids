# ids

Ids of tweets written in Dutch containing the phrase `covid` or `corona` used in the project [PuReGoME](https://research-software-directory.org/projects/puregome). Ids are stored one on each line in zipped text files per day in folders per year. For example, the ids of tweets of Friday 13 March 2020 can be found in the file 2020/20200313.zip

The tweets have been selected with the regular expression `covid|corona` . The expression also selects words of which `covid` or `corona` is a part, like `coronatest`. The language of a tweet is determined by the Twitter metadata field `lang`. Only tweets with the `lang` value `nl` have been included.
 
When using data from this collection, please cite our project paper:

Shihan Wang, Marijn Schraagen, Erik Tjong Kim Sang and Mehdi Dastani, [Public Sentiment on Governmental COVID-19 Measures in Dutch Social Media](https://www.aclweb.org/anthology/2020.nlpcovid19-2.17/). In: Workshop on NLP for COVID-19 (Part 2) at EMNLP 2020 (NLP-COVID19-EMNLP), 20 November 2020.
