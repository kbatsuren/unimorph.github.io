---
layout: page
permalink: /publications/
title: Publications
---

<script src="{{ site.baseurl }}/js/jquery.js"></script>

<link rel="stylesheet" href="{{ site.baseurl }}/css/bib-publication-list.css"/>

The following publications have made use of UniMorph data.

<style>#bibtex {display: block;}</style>

<table id="pubTable" class="display"></table>

<pre id="bibtex" style="display:none;">
{% raw %}
@techreport{sylak2016composition,
  title={The Composition and use of the Universal Morphological Feature Schema ({U}nimorph Schema)},
  author={Sylak-Glassman, John},
year={2016},
pages={1-79},
  institution={Johns Hopkins University}
}

@inproceedings{cotterell-et-al-2016-shared,
  author =      {Cotterell, Ryan and Kirov, Christo and Sylak-Glassman, John and Yarowsky, David and Eisner, Jason and Hulden, Mans},
  title =       {The {SIGMORPHON 2016} Shared Task---Morphological
                 Reinflection},
  booktitle =   {Proceedings of the 14th SIGMORPHON Workshop on
                 Computational Research in Phonetics, Phonology, and
                 Morphology},
  pages =       {10--22},
  year =        {2016},
  month =       aug,
  address =     {Berlin},
  note =        {Supplementary material (4 pages) also available.},
  url =         {http://cs.jhu.edu/~jason/papers/#cotterell-et-al-2016-shared}
    }

    @InProceedings{kann-cotterell-schutze:2017:ACL2017,
  author    = {Kann, Katharina  and  Cotterell, Ryan  and  Schütze, Hinrich},
  title     = {One-Shot Neural Cross-Lingual Transfer for Paradigm Completion},
  booktitle = {Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics (ACL)},
  month     = {August},
  year      = {2017},
  address   = {Vancouver, Canada},
  publisher = {Association for Computational Linguistics},
  url       = {https://arxiv.org/abs/1704.00052}
    }
    @InProceedings{roee-goldberg:2017:ACL2017,
  author    = {Aharoni, Roee  and Goldberg, Yoav Goldberg},
  title     = {One-Shot Neural Cross-Lingual Transfer for Paradigm Completion},
  booktitle = {Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics (ACL)},
  month     = {August},
  year      = {2017},
  address   = {Vancouver, Canada},
  publisher = {Association for Computational Linguistics},
  url       = {https://arxiv.org/abs/1611.01487}
    }

    @InProceedings{nicolai-kondrak:2016:P16-1,
  author    = {Nicolai, Garrett  and  Kondrak, Grzegorz},
  title     = {Leveraging Inflection Tables for Stemming and Lemmatization.},
  booktitle = {Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (ACL)},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {1138--1147},
  url       = {http://www.aclweb.org/anthology/P16-1108}
    }
    
@inproceedings{zhou17acl,
    title = {Multi-space Variational Encoder-Decoders for Semi-supervised Labeled Sequence Transduction},
    author = {Zhou, Chunting and Neubig, Graham},
    booktitle = {The 55th Annual Meeting of the Association for Computational Linguistics (ACL)},
    address = {Vancouver, Canada},
    month = {July},
    url = {http://www.phontron.com/paper/zhou17acl.pdf},
    year = {2017}
}

    @inproceedings{sylak2015universal,
  title={A universal feature schema for rich morphological annotation and fine-grained cross-lingual part-of-speech tagging},
  author={Sylak-Glassman, John and Kirov, Christo and Post, Matt and Que, Roger and Yarowsky, David},
  booktitle={International Workshop on Systems and Frameworks for Computational Morphology},
  pages={72--93},
  year={2015},
  organization={Springer}
}
    
@InProceedings{kann-cotterell-schutze:2017:EACL2017,
  author    = {Kann, Katharina  and  Cotterell, Ryan  and  Schütze, Hinrich},
  title     = {Neural Multi-Source Morphological Reinflection},
  booktitle = {Proceedings of the 15th Conference of the European Chapter of the Association for Computational Linguistics (EACL)},
  month     = {April},
  year      = {2017},
  address   = {Valencia, Spain},
  publisher = {Association for Computational Linguistics},
  pages     = {514--524},
  url       = {http://aclweb.org/anthology/E/E17/E17-1049.pdf}
    }
    
@InProceedings{cotterell-glassman-kirov:2017:EACL2017,
  author    = {Cotterell, Ryan  and  Sylak-Glassman, John  and  Kirov, Christo},
  title     = {Neural Graphical Models over Strings for Principal Parts Morphological Paradigm Completion},
  booktitle = {Proceedings of the 15th Conference of the European Chapter of the Association for Computational Linguistics (EACL)},
  month     = {April},
  year      = {2017},
  address   = {Valencia, Spain},
  publisher = {Association for Computational Linguistics},
  pages     = {759--765},
  url       = {http://www.aclweb.org/anthology/E17-2120},
  note      = {\textcolor{darkcandyapplered}{Outstanding Paper Award}}
    }
    
@InProceedings{glassman-et-al:2017:EACL2017,
  author    = {Kirov, Christo  and  Sylak-Glassman, John  and  Knowles, Rebecca  and  Cotterell, Ryan  and  Post, Matt},
  title     = {A Rich Morphological Tagger for English: Exploring the Cross-Linguistic Tradeoff Between Morphology and Syntax},
  booktitle = {Proceedings of the 15th Conference of the European Chapter of the Association for Computational Linguistics (EACL)},
  month     = {April},
  year      = {2017},
  address   = {Valencia, Spain},
  publisher = {Association for Computational Linguistics},
  pages     = {112--117},
  url       = {http://www.aclweb.org/anthology/E17-2018}
    }

    @InProceedings{KIROV16.1077,
  author = {Kirov, Christo and Sylak-Glassman, John and Que, Roger and Yarowsky, David},
  title = {Very-large Scale Parsing and Normalization of Wiktionary Morphological Paradigms},
  booktitle = {Proceedings of the Tenth International Conference on Language Resources and Evaluation (LREC 2016)},
  year = {2016},
  month = {may},
  date = {23-28},
  location = {Portorož, Slovenia},
  editor = {Nicoletta Calzolari (Conference Chair) and Khalid Choukri and Thierry Declerck and Sara Goggi and Marko Grobelnik and Bente Maegaard and Joseph Mariani and Helene Mazo and Asuncion Moreno and Jan Odijk and Stelios Piperidis},
  publisher = {European Language Resources Association (ELRA)},
  address = {Paris, France},
  isbn = {978-2-9517408-9-1},
  language = {english}
    }

    @InProceedings{sylakglassman-EtAl:2015:ACL-IJCNLP,
  author    = {Sylak-Glassman, John  and  Kirov, Christo  and  Yarowsky, David  and  Que, Roger},
  title     = {A Language-Independent Feature Schema for Inflectional Morphology},
  booktitle = {Proceedings of the 53rd Annual Meeting of the Association for Computational Linguistics and the 7th International Joint Conference on Natural Language Processing (ACL)},
  month     = {July},
  year      = {2015},
  address   = {Beijing, China},
  publisher = {Association for Computational Linguistics},
  pages     = {674--680},
  url       = {http://www.aclweb.org/anthology/P15-2111}
}

    @InProceedings{cotterell-schutze-eisner:2016:P16-1,
  author    = {Cotterell, Ryan  and  Schütze, Hinrich  and  Eisner, Jason},
  title     = {Morphological Smoothing and Extrapolation of Word Embeddings},
  booktitle = {Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (ACL)},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {1651--1660},
  url       = {http://www.aclweb.org/anthology/P16-1156}
}
@Inproceedings{sylak-glassman-cotterell-CLS,
  Author = {Sylak-Glassman, John and Cotterell, Ryan},
  Booktitle = {Proceedings of the 52nd Meeting of the Chicago Linguistic Society (CLS52)},
  Publisher = {Chicago Linguistic Society},
  Title = {Contrastive Morphological Typology and Logical Hierarchies},
  Year = {2015},
  Editorsg = {Kantarovich, Jessica and Truong, Tran and Xherija, Orest},
  url = {https://ryancotterell.github.io/papers/sylak-glassman+cotterell.cls16.pdf}
    }
    
@InProceedings{kann-schutze:2016:P16-2,
  author    = {Kann, Katharina  and  Schütze, Hinrich},
  title     = {Single-Model Encoder-Decoder with Explicit Morphological Representation for Reinflection},
  booktitle = {Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (ACL)},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {555--560},
  url       = {http://anthology.aclweb.org/P16-2090}
}
@InProceedings{ostling:2016:SIGMORPHON,
  author    = {Östling, Robert},
  title     = {Morphological reinflection with convolutional neural networks},
  booktitle = {Proceedings of the 14th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {23--26},
  url       = {http://anthology.aclweb.org/W16-2003}
}
@InProceedings{alegria-etxeberria:2016:SIGMORPHON,
  author    = {Alegria, I\~{n}aki  and  Etxeberria, Izaskun},
  title     = {{EHU} at the SIGMORPHON 2016 Shared Task. A Simple Proposal: Grapheme-to-Phoneme for Inflection},
  booktitle = {Proceedings of the 14th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {27--30},
  url       = {http://anthology.aclweb.org/W16-2004}
}
@InProceedings{nicolai-EtAl:2016:SIGMORPHON,
  author    = {Nicolai, Garrett  and  Hauer, Bradley  and  St Arnaud, Adam  and  Kondrak, Grzegorz},
  title     = {Morphological Reinflection via Discriminative String Transduction},
  booktitle = {Proceedings of the 14th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {31--35},
  url       = {http://anthology.aclweb.org/W16-2005}
}
@InProceedings{liu-mao:2016:SIGMORPHON,
  author    = {Liu, Ling  and  Mao, Lingshuang Jack},
  title     = {Morphological reinflection with conditional random fields and unsupervised features},
  booktitle = {Proceedings of the 14th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {36--40},
  url       = {http://anthology.aclweb.org/W16-2006}
}
@InProceedings{aharoni-goldberg-belinkov:2016:SIGMORPHON,
  author    = {Aharoni, Roee  and  Goldberg, Yoav  and  Belinkov, Yonatan},
  title     = {Improving Sequence to Sequence Learning for Morphological Inflection Generation: The {BIU}-{MIT} Systems for the {SIGMORPHON} 2016 Shared Task for Morphological Reinflection},
  booktitle = {Proceedings of the 14th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {41--48},
  url       = {http://anthology.aclweb.org/W16-2007}
}
@InProceedings{king:2016:SIGMORPHON,
  author    = {King, David},
  title     = {Evaluating Sequence Alignment for Learning Inflectional Morphology},
  booktitle = {Proceedings of the 14th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {49--53},
  url       = {http://anthology.aclweb.org/W16-2008}
}

@InProceedings{sorokin:2016:SIGMORPHON,
  author    = {Sorokin, Alexey},
  title     = {Using longest common subsequence and character models to predict word forms},
  booktitle = {Proceedings of the 14th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {54--61},
  url       = {http://anthology.aclweb.org/W16-2009}
}
@InProceedings{kann-schutze:2016:SIGMORPHON,
  author    = {Kann, Katharina  and  Schütze, Hinrich},
  title     = {{MED}: The {LMU} System for the {SIGMORPHON} 2016 Shared Task on Morphological Reinflection},
  booktitle = {Proceedings of the 14th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {62--70},
  url       = {http://anthology.aclweb.org/W16-2010}
    }
    
@InProceedings{taji-EtAl:2016:SIGMORPHON,
  author    = {Taji, Dima  and  Eskander, Ramy  and  Habash, Nizar  and  Rambow, Owen},
  title     = {The Columbia University - New York University Abu Dhabi SIGMORPHON 2016 Morphological Reinflection Shared Task Submission},
  booktitle = {Proceedings of the 14th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {71--75},
  url       = {http://anthology.aclweb.org/W16-2011}
}

@InProceedings{cotterell-EtAl:2017:K17-20,
  author    = {Cotterell, Ryan  and  Kirov, Christo  and  Sylak-Glassman, John  and  Walther, Géraldine  and  Vylomova, Ekaterina  and  Xia, Patrick  and  Faruqui, Manaal  and  Kübler, Sandra  and  Yarowsky, David  and  Eisner, Jason  and  Hulden, Mans},
  title     = {{CoNLL}-{SIGMORPHON} 2017 Shared Task: Universal Morphological Reinflection in 52 Languages},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {1--30},
  url       = {http://www.aclweb.org/anthology/K17-2001}
}

@InProceedings{bergmanis-EtAl:2017:K17-20,
  author    = {Bergmanis, Toms  and  Kann, Katharina  and  Schütze, Hinrich  and  Goldwater, Sharon},
  title     = {Training Data Augmentation for Low-Resource Morphological Inflection},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {31--39},
  url = {http://www.aclweb.org/anthology/K17-2002}
}

@InProceedings{kann-schutze:2017:K17-20,
  author    = {Kann, Katharina  and  Schütze, Hinrich},
  title     = {The {LMU} System for the {CoNLL}-{SIGMORPHON} 2017 Shared Task on Universal Morphological Reinflection},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {40--48},
  url       = {http://www.aclweb.org/anthology/K17-2003}
}

@InProceedings{makarov-ruzsics-clematide:2017:K17-20,
  author    = {Makarov, Peter  and  Ruzsics, Tatiana  and  Clematide, Simon},
  title     = {Align and Copy: {UZH} at {SIGMORPHON} 2017 Shared Task for Morphological Reinflection},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {49--57},
  url       = {http://www.aclweb.org/anthology/K17-2004}
}

@InProceedings{zhou-neubig:2017:K17-20,
  author    = {Zhou, Chunting  and  Neubig, Graham},
  title     = {Morphological Inflection Generation with Multi-space Variational Encoder-Decoders},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {58--65},
  url       = {http://www.aclweb.org/anthology/K17-2005}
}

@InProceedings{chakrabarty-garain:2017:K17-20,
  author    = {Chakrabarty, Abhisek  and  Garain, Utpal},
  title     = {{ISI} at the {SIGMORPHON} 2017 Shared Task on Morphological Reinflection},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {66--70},
  url       = {http://www.aclweb.org/anthology/K17-2006}
}

@InProceedings{sudhakar-singh:2017:K17-20,
  author    = {Sudhakar, Akhilesh  and  Singh, Anil Kumar},
  title     = {Experiments on Morphological Reinflection: {CoNLL}-2017 Shared Task},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {71--78},
  url       = {http://www.aclweb.org/anthology/K17-2007}
}

@InProceedings{nicolai-EtAl:2017:K17-20,
  author    = {Nicolai, Garrett  and  Hauer, Bradley  and  Motallebi, Mohammad  and  Najafi, Saeed  and  Kondrak, Grzegorz},
  title     = {If you can't beat them, join them: {T}he University of {A}lberta system description},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {79--84},
  url       = {http://www.aclweb.org/anthology/K17-2008}
}

@InProceedings{zhu-li-li:2017:K17-20,
  author    = {Zhu, Qile  and  Li, Yanjun  and  Li, Xiaolin},
  title     = {Character Sequence-to-Sequence Model with Global Attention for Universal Morphological Reinflection},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {85--89},
  url       = {http://www.aclweb.org/anthology/K17-2009}
}

@InProceedings{silfverberg-EtAl:2017:K17-20,
  author    = {Silfverberg, Miikka  and  Wiemerslage, Adam  and  Liu, Ling  and  Mao, Lingshuang Jack},
  title     = {Data Augmentation for Morphological Reinflection},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {90--99},
  url       = {http://www.aclweb.org/anthology/K17-2010}
}

@InProceedings{senuma-aizawa:2017:K17-20,
  author    = {Senuma, Hajime  and  Aizawa, Akiko},
  title     = {Seq2seq for Morphological Reinflection: When Deep Learning Fails},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {100--109},
  url       = {http://www.aclweb.org/anthology/K17-2011}
}

@InProceedings{ostling-bjerva:2017:K17-20,
  author    = {Östling, Robert  and  Bjerva, Johannes},
  title     = {{SU-RUG} at the {CoNLL-SIGMORPHON} 2017 Shared Task: Morphological Inflection with Attentional Sequence-to-Sequence Models},
  booktitle = {Proceedings of the CoNLL SIGMORPHON 2017 Shared Task: Universal Morphological Reinflection},
  month     = {August},
  year      = {2017},
  address   = {Vancouver},
  publisher = {Association for Computational Linguistics},
  pages     = {110--113},
  url       = {http://www.aclweb.org/anthology/K17-2012}
}
{% endraw %}
</pre>
<script type="text/javascript" src="{{ site.baseurl }}/js/jquery.js"></script>
<script type="text/javascript" src="{{ site.baseurl }}/build/bib-list.js"></script>
<script type="text/javascript">
	$(document).ready(function() {
        bibtexify("#bibtex", "pubTable", {'tweet': 'vkaravir'});
    });
</script>
