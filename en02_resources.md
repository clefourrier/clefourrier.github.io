
# Research {.ref}
**Research topics**: deep learning, low resource NMT, computational historical linguistics, cognate prediction

### My favorite publications
- [Can Cognate Prediction Be Modelled as a Low-Resource Machine Translation Task?](https://hal.inria.fr/hal-03243380/file/Is_Cognate_Prediction_a_Low_Resource_Machine_Translation_Task__ACL2021Findings-2.pdf) (ACL Findings): we proved that neural machine translation methods are applicable to cognate prediction, defined in which contexte, as well as defined theoretical differences between both tasks.
- [Methodological Aspects of Developing and Managing an Etymological Lexical Resource: Introducing EtymDB-2.0](https://hal.inria.fr/hal-02678100/document) (LREC 2020): we both introduced an etymological database as well as guidelines to create or manage your own!


### Publications
Full page list on [google scholar](https://scholar.google.com/citations?user=UiK-jPcAAAAJ&hl=en) or
[hal](https://haltools.inria.fr/Public/afficheRequetePubli.php?auteur_exp=Cl%C3%A9mentine%2C+Fourrier&CB_auteur=oui&CB_titre=oui&CB_article=oui&CB_DOI=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&CB_rubriqueDiv=oui&Fen=Aff&css=../css/VisuRubriqueEncadre.css).

<div class="my_widget">
Widget list below (please scroll):

<IFRAME width="100%" height="300" src="https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?auteur_exp=cl%C3%A9mentine%2C+fourrier&annee_publideb=2020&CB_titre=oui&CB_article=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=https://clefourrier.github.io/website.css" FRAMEBORDER="1" ></IFRAME>
</div>

### Talks

#### Conferences
- 08/2021: ACL Findings: *Can Cognate Prediction Be Modelled as a Low-Resource Machine Translation Task?* ([Slides](https://d3smihljt9218e.cloudfront.net/lecture/26166/slideshow/4a2b9ebbfc0e00f0b33ea5d69cb949f4.pdf))
- 08/2021: LChange'21 Workshop : *Can Cognate Prediction Be Modelled as a Low-Resource Machine Translation Task?* ([Poster](https://d3smihljt9218e.cloudfront.net/lecture/26166/poster_document/e107a37a833ef9d91fbb3e04ba658928.pdf))
- 05/2020: TALN-RECITAL: *Evolution phonologique des langues et réseaux de neurones* ([Talk](https://videos.univ-lorraine.fr/video.php?id=9730))

#### Seminars
- 02/2020: Inria, ALMAnaCH seminar: *Learning Sound Correspondences: What about Neural Networks?*

#### Paper study groups
- 10/2021: *Multilingual Agreement for Multilingual Neural Machine Translation - Yang et al 2021* ([Slides](https://drive.google.com/file/d/12FLg1FMxZLU76UtP5RIgf0NJWjx7kLmE/view?usp=sharing))
- 02/2021: *On the Dangers of Stochastic Parrots: Can Language Models be Too Big - Bender et al 2021* ([Slides](https://drive.google.com/file/d/1q7_KMMTj4dPRD6si9OgIOT-GWujOv-8C/view?usp=sharing))
- 05/2020: *Dataset for Temporal Analysis of English-French Cognates - Frossard et al 2020* ([Slides](https://drive.google.com/file/d/1puLEBVx-KhA28qXdxnJC8KZRTj9rWjep/view?usp=sharing))
- 01/2020: *Universal Adversarial Triggers for Attacking and Analysing NLP - Wallace et al 2019* ([Slides](https://drive.google.com/file/d/1L-dfBzTV7Tsthv6FEOnvOqg4SyFQynan/view?usp=sharing))
- 07/2019: *Identifying and Controlling Important Neurons in NMT, Bau et al 2019* ([Slides](https://drive.google.com/file/d/16OfrE83lA5JA2_ZMuWDqydYiIBcTwlWr/view?usp=sharing))
- 04/2019: *The Potential of Automatic Word Comparision for Historical Linguistics - List et al 2017* ([Slides](https://drive.google.com/file/d/1HFpShYeS2MY1-jiHL9Pd9dbFqWXeZpET/view?usp=sharing))
- 03/2019: *Automatic Inference of Sound Correspondence Patterns Across Multiple Languages - List 2018* ([Slides](https://drive.google.com/file/d/1PRK6MZ5YHxfa4uLnYXFxLXNhamhI4VpM/view?usp=sharing))


# NLP Resources {#resources .ref}
### Database
#### EtymDB2 - Etymological database, [here](https://github.com/clefourrier/EtymDB): 
<img src="img/logos/etymdb2_logo.png" alt="The logo of EtymDB2: a tree sprouting of a database" width="65px" style="float: left; margin: 0 15px 0 0;"> Fine grained etymological database which differentiates between inheritance, cognacy, borrowing, and different types of composition.  
It comes with several Jupyter notebooks for data analysis, including one to draw your own language trees from the word links. (Perl, Jupyter notebooks)  
Details in our [paper](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.392.pdf): *Methodological Aspects of Developing and Managing an Etymological Lexical Resource: Introducing EtymDB 2.0.* 

<br/><br/>

### Software
#### PLexGen - Conlang generator, [here](https://github.com/clefourrier/PLexGen):
If you want to try conlanging, you can with PLexGen, my phonetic lexicon generator and sound change applier!  
Provide your language shape (phonetics and phonotactics) and sound changes, and it will randomly generate a proto-language and its daughter languages after your specifications! (Python)

#### CopperMT - Cognate Prediction Per Machine Translation, [here](https://github.com/clefourrier/CopperMT):
Scripts and algos to run cognate prediction tasks using MT (either MOSES for SMT or my multiway encoder decoder based on fairseq for NMT).
Details in our [paper](): *Is Cognate Prediction a Machine Translation Task?* 


