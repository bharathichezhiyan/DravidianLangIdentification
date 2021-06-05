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


