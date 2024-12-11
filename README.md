This repository will provide direct access to the data and code used to construct Tiresias: The Ancient Mediterranean Religions Source Database
main site: https://tiresias.haifa.ac.il/

The following files are included: 

* titlesa.csv - a list of ancient work titles included in the database, keyed to an identifying number and in most cases including also metadata on language and date. 

* bookreferences2.csv - a list of modern books from which the indices were taken, keyed to an identifying number.

* all_subjects - a folder containing the main database, with subjects listed by the first three letters (in order not to have tens of thousands of files).
all_subjects csvs include the following columns:

  *C - ID for each line
  
  *book bibliographic info - number of modern book from which the info was taken (keyed to bookreferences2.csv)

  *page - page in modern book from which the info was taken

  *ref - reference in ancient text

  *subject_x - lemmatized and stemmed subject words

  *subject_y - original subject as appearing in index

  *number - ancient work number (keyed to titles.csv)
			
	


Tiresias: The Ancient Mediterranean Religions Source Database provides access to references to ancient texts according to topic, mostly on religion, c. -800 BCE to 800 CE in the Mediterranean area. In many cases, direct access to full text and/or translation is also available. Topic tagging is based on existing subject indices from scholarly books, allowing highly detailed topic resolution. The site is in development, and currently includes about 22 million references keyed to 180,000 subjects.

Currently, the site includes four types of searches by subject:
For validated results, where the reference is tagged with the subject in more than one book. This is the default search, and retrieves also a list of all sub-subjects and secondary sources.
For non-validated primary text results, where the reference is tagged with the subject only once, in one book.
For secondary literature only, retrieves a list of all sub-subjects and secondary sources.
Furthermore, it is possible to search by primary text reference.

Two visualizations are available:
A network visualization of one-word subjects linked to a specific subject provided by the user (i.e., present on the same page of secondary sources as that subject).
A heatmap visualization of the same, but here divided according to the date of the primary texts tagged by these subjects.

The construction of the database is based on the following method. Many research volumes in ancient history are published with two indices: one for subjects, topics or terms, and one for ancient text references (the latter is also known as an index locorum). Using these indices, each page of the indexed book can be identified as relating to specific subjects as well as specific ancient texts, indicating with a certain probability that these text references can be tagged as related to these subjects. In order to bring this probability closer to 100%, we assess the overlap from a number of books of this connection between text reference and subject. These tags are combined to create a general database of subjects of ancient texts. The database is thus based on existing expert-made indices, unified and assisted by digital means.
The database includes general subjects, ideas, names and places, almost all in English; the subjects are the same you would find in a good subject index of a book.

Current stats (as of 2 March, 2024):
Total number of reference tags (validated and nonvalidated): 29,598,020
Number of reference tags (validated): 20,425,010
Number of subject tags: 224,385
Number of ancient texts: 12,484
Number of modern book indices: 832

The site is part of a digital humanities research project investigating innovative methods for text topic retrieval, conducted by Moshe Blidstein of the General History Department and the Haifa Center for Mediterranean History and Daphne Raban, the Department of Information & Knowledge Management, both at the University of Haifa.
For information and suggestions, please contact mblidstei@univ.haifa.ac.il.
# tiresias
