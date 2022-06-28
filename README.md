# CyberBlogDataset
This is the repository that holds a corpus of text from various cybersecurity blogs, in various formats, such as json with metadata, and by paragraph.

The json folder holds all of the text in json and jsonl form with meta data including, the source, the link and the data published and accessed.

The Paragraphs folder holds all of the text broken up into paragraphs, with each paragraph being its own file. The breaking up into paragraphs was done using NLP techniques from the raw text in the json format. A list of all file names of the paragraphs is in this repository as well.
The filenames for the paragraphs follow a format with the title of the article (the last part of the link it came from) then !! then what part of that article it is.

The Sentences folder holds files with the text data broken up into sentences. The text is broken up into sentences via the SpaCy sentencizer. There is one file per article and each sentence is separated by two newline characters. A list of all the filenames is avaiable in this repository.

This dataset was created as a part of the paper "Recognizing and Extracting Cybersecurity Entities from Text" by Casey Hanks, Michael Maiden, Priyanka Ranade, Tim Finin, and Anupam Joshi.


