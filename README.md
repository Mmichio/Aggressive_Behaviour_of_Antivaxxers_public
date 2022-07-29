# Aggressive_Behaviour_of_Antivaxxers_public
This is the repository for code and data of the paper "Aggressive Behaviour of Anti-vaxxers and Their Toxic Replies in English and Japanese."  
Paper: https://www.nature.com/articles/s41599-022-01245-x

### Data
- English tweets (about 8.6M tweets)
  - https://www.dropbox.com/s/2ckwr447dexu2m8/df_vaccine_all_en_ids.csv?dl=0

- Japanese tweets (about 2.0M tweets)
  - https://www.dropbox.com/s/pc5vtgnkpfanomo/df_vaccine_all_ja_ids.csv?dl=0

We release only tweet ids following the [Twitter policy](https://developer.twitter.com/en/developer-terms/more-on-restricted-use-cases).

### Code
- analysis_en.ipynb
  - all processes and visualization for English tweets
- analysis_ja.ipynb
  - all processes and visualization for Japanese tweets
- wordcloud_ja.ipynb
  - visualization of wordcloud for translated Japanese tweets into English


 
### Caveat
You need to use external tools and APIs to complete the processes.
- Twitter API for getting tweets using tweet ids
- [Gephi](https://gephi.org/) for visualizing and clustering networks.
- Perspective API for scoring the toxicity of tweets
- Google translate API for translating the Japanese tweets into English

and the codes are not clean.. sorry about this.

Also, if you want to use the codes or data, please cite our paper.
```
Miyazaki, K., Uchiba, T., Tanaka, K., Sasahara, K. Aggressive behaviour of anti-vaxxers and their toxic replies in English and Japanese. Humanit Soc Sci Commun 9, 229 (2022). https://doi.org/10.1057/s41599-022-01245-x
```
