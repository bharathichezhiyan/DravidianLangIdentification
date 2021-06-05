# DravidianLangIdentification
Dravidian Language Identification Dataset -Findings of the VarDial Evaluation Campaign 2021

== Data Format ==

The test data contains the following file:

	Dravidian-testset-DLI-withoutlabels.tsv - testing set

Each line in the test.txt file is in the format:

	text-sample 1
	text-sample 2
	...
	text-sample N


== Submission ==

Each participant is allowed to submit 3 runs per subtask to:
	
	bharathiraja.akr@gmail.com 

Each line in the submission file DLI-run-X-[team_name].txt file is in the format:

	label 1
	label 2
	...
	label N

The labels must be given in the same order as the test samples listed in Dravidian-testset-DLI-withoutlabels.tsv. The participants must provide labels for all the test samples. Each submission (run) must be accompanied by a DLI-readme-run-X-[team_name].txt file containing a one-paragraph description of the respective submission, where X is the run number (1, 2 or 3). 

For example, if the team name is "Ghostbusters", the first submission to subtask 3 should contain two files:
	DLI-run-1-Ghostbusters.txt
	DLI-readme-run-1-Ghostbusters.txt


== Task Description ==

In the 2021 Dravidian Language Identification (DLI) shared task, participants have to train a model on comments written in Roman script.  Dravidian languages are spoken mainly in the south of India. The four major literary Dravidian languages are Tamil (ISO 639-3: tam), Telugu (ISO 639-3: tel), Malayalam (ISO 639-3: mal), and Kannada (ISO 639-3: kan). Tamil, Malayalam and Kannada fall under the South Dravidian subgroup, whereby Telugu belongs to the South Central Dravidian subgroup.  All four languages have official status in the Government of India. Outside India, Tamil also has official status in Sri Lanka and Singapore. However, the language resource for these languages is under-developed.
Our corpora contains all the three types of code-mixed sentences Inter-Sentential switch, Intra-Sentential switch and Tag switching. All  comments were written in Roman script (Non-native script) with either one of the south Dravidian (Tamil, Malayalam, and Kannada) grammar with English lexicon or English grammar with south Dravidian lexicons. The comment will be written in Roman Script with different types of code-mixing. The language tag of the comment will be given.
The challenge of the task is to identify the language of the given comment. It is challenge task since Tamil, Malayalam and Kannada are closely related language some of the words are common in all these languages. The participants has to train a system to identify the language of the comment.  Our dataset size is 16,672 comments for training. We can name the task as  DLI- Dravidian Language Identification.

== Evaluation ==


The macro-averaged F1 score will be used to rank the participants.


== Organizers ==

Bharathi Raja Chakravarthi, National University of Ireland Galway, Ireland (bharathiraja.akr@gmail.com)
Ruba Priyadharahsini, ULTRA Arts and Science College, Madurai, India (rubapriyadharshini.a@gmail.com)
Eswari Rajagopal, National Institute of Technology Tiruchirappalli, India (eswari@nitt.edu)

if you are using the paper then cite
```
@inproceedings{chakravarthi-etal-2021-findings,
    title = "Findings of the {V}ar{D}ial Evaluation Campaign 2021",
    author = "Chakravarthi, Bharathi Raja  and
      Mihaela, Gaman  and
      Ionescu, Radu Tudor  and
      Jauhiainen, Heidi  and
      Jauhiainen, Tommi  and
      Lind{\'e}n, Krister  and
      Ljube{\v{s}}i{\'c}, Nikola  and
      Partanen, Niko  and
      Priyadharshini, Ruba  and
      Purschke, Christoph  and
      Rajagopal, Eswari  and
      Scherrer, Yves  and
      Zampieri, Marcos",
    booktitle = "Proceedings of the Eighth Workshop on NLP for Similar Languages, Varieties and Dialects",
    month = apr,
    year = "2021",
    address = "Kiyv, Ukraine",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2021.vardial-1.1",
    pages = "1--11",
    abstract = "This paper describes the results of the shared tasks organized as part of the VarDial Evaluation Campaign 2021. The campaign was part of the eighth workshop on Natural Language Processing (NLP) for Similar Languages, Varieties and Dialects (VarDial), co-located with EACL 2021. Four separate shared tasks were included this year: Dravidian Language Identification (DLI), Romanian Dialect Identification (RDI), Social Media Variety Geolocation (SMG), and Uralic Language Identification (ULI). DLI was organized for the first time and the other three continued a series of tasks from previous evaluation campaigns.",
}
@inproceedings{chakravarthi-2020-hopeedi,
    title = "{H}ope{EDI}: A Multilingual Hope Speech Detection Dataset for Equality, Diversity, and Inclusion",
    author = "Chakravarthi, Bharathi Raja",
    booktitle = "Proceedings of the Third Workshop on Computational Modeling of People's Opinions, Personality, and Emotion's in Social Media",
    month = dec,
    year = "2020",
    address = "Barcelona, Spain (Online)",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.peoples-1.5",
    pages = "41--53",
    abstract = "Over the past few years, systems have been developed to control online content and eliminate abusive, offensive or hate speech content. However, people in power sometimes misuse this form of censorship to obstruct the democratic right of freedom of speech. Therefore, it is imperative that research should take a positive reinforcement approach towards online content that is encouraging, positive and supportive contents. Until now, most studies have focused on solving this problem of negativity in the English language, though the problem is much more than just harmful content. Furthermore, it is multilingual as well. Thus, we have constructed a Hope Speech dataset for Equality, Diversity and Inclusion (HopeEDI) containing user-generated comments from the social media platform YouTube with 28,451, 20,198 and 10,705 comments in English, Tamil and Malayalam, respectively, manually labelled as containing hope speech or not. To our knowledge, this is the first research of its kind to annotate hope speech for equality, diversity and inclusion in a multilingual setting. We determined that the inter-annotator agreement of our dataset using Krippendorff{'}s alpha. Further, we created several baselines to benchmark the resulting dataset and the results have been expressed using precision, recall and F1-score. The dataset is publicly available for the research community. We hope that this resource will spur further research on encouraging inclusive and responsive speech that reinforces positiveness.",
}
@inproceedings{hande-etal-2020-kancmd,
    title = "{K}an{CMD}: {K}annada {C}ode{M}ixed Dataset for Sentiment Analysis and Offensive Language Detection",
    author = "Hande, Adeep  and
      Priyadharshini, Ruba  and
      Chakravarthi, Bharathi Raja",
    booktitle = "Proceedings of the Third Workshop on Computational Modeling of People's Opinions, Personality, and Emotion's in Social Media",
    month = dec,
    year = "2020",
    address = "Barcelona, Spain (Online)",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.peoples-1.6",
    pages = "54--63",
    abstract = "We introduce Kannada CodeMixed Dataset (KanCMD), a multi-task learning dataset for sentiment analysis and offensive language identification. The KanCMD dataset highlights two real-world issues from the social media text. First, it contains actual comments in code mixed text posted by users on YouTube social media, rather than in monolingual text from the textbook. Second, it has been annotated for two tasks, namely sentiment analysis and offensive language detection for under-resourced Kannada language. Hence, KanCMD is meant to stimulate research in under-resourced Kannada language on real-world code-mixed social media text and multi-task learning. KanCMD was obtained by crawling the YouTube, and a minimum of three annotators annotates each comment. We release KanCMD 7,671 comments for multitask learning research purpose.",
}
@inproceedings{chakravarthi-etal-2020-sentiment,
    title = "A Sentiment Analysis Dataset for Code-Mixed {M}alayalam-{E}nglish",
    author = "Chakravarthi, Bharathi Raja  and
      Jose, Navya  and
      Suryawanshi, Shardul  and
      Sherly, Elizabeth  and
      McCrae, John Philip",
    booktitle = "Proceedings of the 1st Joint Workshop on Spoken Language Technologies for Under-resourced languages (SLTU) and Collaboration and Computing for Under-Resourced Languages (CCURL)",
    month = may,
    year = "2020",
    address = "Marseille, France",
    publisher = "European Language Resources association",
    url = "https://www.aclweb.org/anthology/2020.sltu-1.25",
    pages = "177--184",
    abstract = "There is an increasing demand for sentiment analysis of text from social media which are mostly code-mixed. Systems trained on monolingual data fail for code-mixed data due to the complexity of mixing at different levels of the text. However, very few resources are available for code-mixed data to create models specific for this data. Although much research in multilingual and cross-lingual sentiment analysis has used semi-supervised or unsupervised methods, supervised methods still performs better. Only a few datasets for popular languages such as English-Spanish, English-Hindi, and English-Chinese are available. There are no resources available for Malayalam-English code-mixed data. This paper presents a new gold standard corpus for sentiment analysis of code-mixed text in Malayalam-English annotated by voluntary annotators. This gold standard corpus obtained a Krippendorff{'}s alpha above 0.8 for the dataset. We use this new corpus to provide the benchmark for sentiment analysis in Malayalam-English code-mixed texts.",
    language = "English",
    ISBN = "979-10-95546-35-1",
}
@inproceedings{chakravarthi-etal-2020-corpus,
    title = "Corpus Creation for Sentiment Analysis in Code-Mixed {T}amil-{E}nglish Text",
    author = "Chakravarthi, Bharathi Raja  and
      Muralidaran, Vigneshwaran  and
      Priyadharshini, Ruba  and
      McCrae, John Philip",
    booktitle = "Proceedings of the 1st Joint Workshop on Spoken Language Technologies for Under-resourced languages (SLTU) and Collaboration and Computing for Under-Resourced Languages (CCURL)",
    month = may,
    year = "2020",
    address = "Marseille, France",
    publisher = "European Language Resources association",
    url = "https://www.aclweb.org/anthology/2020.sltu-1.28",
    pages = "202--210",
    abstract = "Understanding the sentiment of a comment from a video or an image is an essential task in many applications. Sentiment analysis of a text can be useful for various decision-making processes. One such application is to analyse the popular sentiments of videos on social media based on viewer comments. However, comments from social media do not follow strict rules of grammar, and they contain mixing of more than one language, often written in non-native scripts. Non-availability of annotated code-mixed data for a low-resourced language like Tamil also adds difficulty to this problem. To overcome this, we created a gold standard Tamil-English code-switched, sentiment-annotated corpus containing 15,744 comment posts from YouTube. In this paper, we describe the process of creating the corpus and assigning polarities. We present inter-annotator agreement and show the results of sentiment analysis trained on this corpus as a benchmark.",
    language = "English",
    ISBN = "979-10-95546-35-1",
}```
