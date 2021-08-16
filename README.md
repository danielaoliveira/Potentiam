# Potentiam

This repository contains:
* Potentiam, our dataset of pieces of online texts manually labeled with influence cues.
* The coding manual used in the qualitative analysis.
* Our paper contains details about the dataset and our coding methodology, as well as a statistical analysis of the dataset and its use to expose influence cues in text using machine learning. This paper can be also found at: https://arxiv.org/abs/2107.10655 

For the Deceptive Texts Group, we mixed 492 Facebook ads created by the Russian Internet Research Agency (IRA), 130 known fake news articles, and 460 phishing emails. 
* Facebook IRA Ads. We leveraged a dataset of 3,517 Facebook ads created by the Russian IRA and made publicly available to the U.S. House of Representatives Permanent Select Committee on Intelligence  by Facebook after internal audits. These ads were a small representative sample of over 80K organic content identified by the Committee and are estimated to have been exposed to over 126M Americans between June 2015 and August 2017. After discarding ads that did not have text entry, the dataset was decreased to 3,286 ads, which were mostly (52.8%) posted in 2016 (U.S. election year). We randomly selected 492 for inclusion. 
* Fake News. We leveraged a publicly available dataset of nearly 17K news labeled as fake or real collected from PoliticFact.com, a reputable source of fact finding. We randomly selected 130 fake news ranging from 110-200 words dated between 2007 to 2020. 
* Phishing Emails. To gather our dataset, we collected approximately 15K known phishing emails from multiple public sources. We randomly selected 460 of these emails ranging from 50-150 words to be included as part of the Deceptive Texts.

For the Hyperpartisan News and Mainstream News Groups, we used a public dataset composed of 2.7M news articles and essays from 27 American publications dated from 2013 to early 2020. We first selected articles ranging from 50-200 words and then classified them as left, right, or center news according to the AllSides Bias Rating. For inclusion in the Hyperpartisan News Group, we randomly selected 506 right news and 497 left news; the former were dated from 2016 to 2017 and came from two publications sources (Breitbart and National Review) while the latter were dated from 2016 to 2019 and came from six publications (Buzzfeed News, Mashable, New Yorker, People, VICE, and Vox). To compose the Mainstream News Group, we randomly selected 974 center news from all seven publications (Business Insider, CNBC, NPR, Reuters, TechCrunch, The Hill, and Wired) dated from 2014 to 2019.

The development of this dataset was supported by the National Science Foundation under Grant No. 2028734 and by the University of Florida Seed Fund award P0175721. This material is based upon work supported by (while serving at) the National Science Foundation.

Team: 

PI: Dr. Daniela Oliveira, Department of Electrical and Computer Engineering, University of Florida (daniela@ece.ufl.edu)

co-PI: Dr. Juliana Fernandes, Department of Advertising, University of Florida (juliana@jou.ufl.edu)

Dr. Luiz Giovanini, Department of Electrical and Computer Engineering, University of Florida

Mirela Silva, PhD Student, Department of Electrical and Computer Engineering, University of Florida

Dr. Hanyu Shi

Lauren Czech, PhD Student, Department of Electrical and Computer Engineering, University of Florida


# How to cite us

Our repository does not contain sensitive material, nor PII. Therefore, it is publicly available to the research community. **Upon use, please cite as follows**:

**Dataset**: 

*@misc{potentiam2021_dataset, 
title={Potentiam: A Labeled Dataset of Influence Cues in Online Text}, 
author={Silva, Mirela, and Giovanini, Luiz and Czech, Lauren and Fernandes, Juliana and Oliveira, Daniela}, 
year={2021}}*

*M. Silva, L. Giovanini, L. Czech, J. Fernandes, and D. Oliveira, "Potentiam: A Labeled Dataset of Influence Cues in Online Text," 2021. Available at: https://github.com/danielaoliveira/Potentiam*

**Lumen**: 

*@article{shi2021lumen,
  title={Lumen: A Machine Learning Framework to Expose Influence Cues in Text},
  author={Shi, Hanyu and Silva, Mirela and Capecci, Daniel and Giovanini, Luiz and Czech, Lauren and Fernandes, Juliana and Oliveira, Daniela},
  journal={arXiv preprint arXiv:2107.10655},
  year={2021}
  url = {https://arxiv.org/abs/2107.10655}}*

*S. Hanyu, M. Silva, D. Capecci, L. Giovanini, L. Czech, J. Fernandes, and D. Oliveira, "Lumen: A Machine Learning Framework to Expose Influence Cues in Text," 2021. arXiv preprint arXiv:2107.10655.*
