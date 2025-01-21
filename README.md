# Key Word Searcher
A Java software provides a graphical user interface to search and visualise keywords in local documents and online web pages based on their word form, lemma, or [POS tag](https://www.ling.upenn.edu/courses/Fall_2003/ling001/penn_treebank_pos.html).

Authors: Hyunjoo Cho ([@annettehjc](https://github.com/annettehjc)), Lina M. Longar ([@linalongar](https://github.com/linalongar)), Nikita L. Beklemishev ([@lilovyjgrib](https://github.com/lilovyjgrib)), Szymon T. Kossowski ([szymonkossowski](https://github.com/szymonkossowski))

### Instructions

1. Download .jar file.
2. Run it (Java SDK needed).
3. By clicking on "file" a file navigator pops up. Alternatively, click URL button and paste the link to a web page.
4. Choose the search options you want (multiplace choice is possible)
5. Write the corresponding terms for each option. 
6. Choose to display the whole sentence or just a few neighbouring words.
7. Choose if you want case-sensitivity to be on or not. 
8. Click on the magnifying glass to search.
9. On the left hand side, you will see the output result, and on the right hand side **recent searches** and **text statistics** will be saved. 
10. Optionally, save your search as XML.


### Resources:

- **Swing environment** (GUI).
- **Apache OpenNLP** library (models: _opennlp-en-ud-ewt-tokens-1.0-1.9.3.bin_, _opennlp-en-ud-ewt-sentence-1.0-1.9.3.bin_, _opennlp-en-ud-ewt-pos-1.0-1.9.3.bin_, _en-lemmatizer2.bin_).
- **JSoup** library (web scraping).
- **DOM Parser** (exporting to XML).

---
**Note**    
The source code of this project is not yet publicly available because parts of this program are a graded task for
students enrolled in the Computational Linguistics program @ University of Tübingen.
