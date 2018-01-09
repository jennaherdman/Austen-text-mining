#Welcome! 

This is the first draft of an upcoming blog post about text mining Jane Austen novels, and the potential of this research to ask new research questions. I experiment with text mining tool Voyant and Google Ngrams. As an expanded print version of this project is currently being evaluated for a class, I will update the full analysis of the graphs at a further date. 

[Follow this link for more information about Voyant](http://docs.voyant-tools.org/tools/).

##Why Text Mine Austen? 

* well-known, canonical work
* texts freely available for download and manipulation using Project Gutenberg 
* scholarly and pedagogical importance - how can we keep students interested in reading and analyzing Austen? 

##Google Ngram graph

* codex is mysterious: represents the relative frequencies of a term or a phrase in all of the books published that year and that are archived on Google books 

![Austen Trends](https://github.com/jennaherdman/Austen-text-mining/blob/master/unspecified.jpeg?raw=true)

[Follow this link for an interactive version of this graph](https://books.google.com/ngrams/graph?content=Northanger+Abbey%2CPride+and+Prejudice%2CSense+and+Sensibility%2CMansfield+Park&year_start=1800&year_end=2010&corpus=15&smoothing=3&share=&direct_url=t1%3B%2CNorthanger%20Abbey%3B%2Cc0%3B.t1%3B%2CPride%20and%20Prejudice%3B%2Cc0%3B.t1%3B%2CSense%20and%20Sensibility%3B%2Cc0%3B.t1%3B%2CMansfield%20Park%3B%2Cc0). 

###Findings 
* opted out of using *Emma* or *Persuasion* as I thought the titles were too generic to return accurate results 
* *Pride and Prejudice* is always the most popular 
* all of the trends are somewhat similar: when one rises in popularity, so do the other ones 
* *Northanger Abbey* is always the least popular - interesting because both NA and P&P were originally written in the late 1790’s, but were revised for publication several years later 
* what books are contained in this codex? Are there several reprints of certain books? 

##Romantic Rivalries in Jane Austen 

* used the Terms tool on *Voyant* to look at name frequencies of the romantic hero and rival in four Austen novels 
* challenging because need to know which name the author calls him by - i.e. just searching for “Darcy” is insufficient because it might refer to his sister, “Miss Darcy”
* puts a character talking about him on equal footing with an actual appearance  

###*Pride and Prejudice* 

![Pride and Prejudice](https://github.com/jennaherdman/Austen-text-mining/blob/master/p%20and%20p%20terms.jpeg?raw=true)

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=aa5342d4d854354fea80232f149ecf5e&query=wickham*&query=mr%20darcy&withDistributions=raw&docIndex=0&mode=document&view=Trends) 

Findings 
* moments of intersection between the two men 
* Wickham disappears and reappears consistently - at the end, he becomes important not as a rival for Elizabeth’s heart, but because he elopes with her sister 
* Darcy triumphs at the end 

###*Sense and Sensibility* 

![Sense and Sensibility](https://github.com/jennaherdman/Austen-text-mining/blob/master/sense-trends.jpeg?raw=true)

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=b521a70350c06325e841ed66af5c4e29&query=colonel&query=willoughby*&withDistributions=raw&mode=document&view=Trends).


Findings 
* Willoughby appears far more important than Colonel Brandon, except for in the last few segments 
* Brandon is steady but not dramatic - the aesthetic quality of the graph reflects the drama of the novel 
* in comparison to P&P, Willougby’s trend more closely resembles Darcy’s 

###*Northanger Abbey* and *Mansfield Park*


![Northanger Abbey](https://github.com/jennaherdman/Austen-text-mining/blob/master/northanger-trends.png?raw=true)

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=e218ddd3ea097161c163a80f75c38f85&query=john|mr.%20thorpe*&query=henry|mr.%20tilney&withDistributions=raw&docIndex=0&mode=document&view=Trends).


![Mansfield Park](https://github.com/jennaherdman/Austen-text-mining/blob/master/mansfield.png?raw=true)

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=a99f30c20fdc2d887c74f9bc78c2eddf&query=edmund&query=henry|mr.%20crawford&withDistributions=raw&docIndex=0&mode=document&view=Trends).


Findings 
* far more similar to each other than to P&P and S&S 
* the trends in each graph seem to mirror one another in how they increase and decrease 
* *Northanger Abbey* sees the hero/husband be more prominent throughout, while in *Mansfield Park* the rival is far more prominent - is there a mistake in the final graph? 
* because the final graph is so different from the first three, I am suspicious about its authenticity

##Links - collocation terms in *Sense and Sensibility* 

![S&S links](https://github.com/jennaherdman/Austen-text-mining/blob/master/sense-collocation.jpeg?raw=true) 

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=b521a70350c06325e841ed66af5c4e29&mode=corpus&view=CollocatesGraph).


* why such a discrepancy between “Marianne” and “Marianne’s”? 
* requires a lot of intuition/cultivation by the person using the tool, not simply generated 
* necessitates “playing” with the graph 

##Conclusions 

* some of Voyant’s tools are inaccessible, require a lot of concentration in clicking and hand-eye coordination 
* the act of creating the graph is a form of reading and analysis: making informed choices about how to structure and program each one 
* future studies could look at sentiment analysis by chapter - [see Julia Silge](http://juliasilge.com/blog/Life-Changing-Magic/). 
* useful for undergraduate classes: unpacking the text, looking for patterns, critiquing their results 

##Thank you! 


##Works Cited 

Austen, Jane. Mansfield Park. n.p. n.d. Project Gutenberg. Web. 28 Oct. 2016. 

---. Northanger Abbey. n.p. n.d. Project Gutenberg. Web. 28 Oct. 2016.

---. Pride and Prejudice. n.p. n.d. Project Gutenberg. Web. 28 Oct. 2016.

---. Sense and Sensibility. n.p. n.d. Project Gutenberg. Web. 28 Oct. 2016.

Hayles, N. Katherine. “How We Read: Close, Hyper, Machine.” ADE Bulletin 150 (2010): 
62-79.

Ramsay, Stephen. “Toward an Algorithmic Criticism.” Literary and Linguistic Computing 18.2 (2003): 167-174. 

Herdman, Jenna. “Tool Tutorial: Text Analysis.” GitBook, 2016. Web. Accessed 28 Oct 2016. < https://jennaherdman.gitbooks.io/a-digital-humanities-primer-for-english-students/
content/Text%20Analysis%20Assignment.html>

Silge, Julia. “The Life-Changing Magic of Tidying Text.” data science ish. Web. 29 Apr. 2016. Accessed 27 Oct. 2016.

Sinclair, Stéfan and Geoffrey Rockwell. "About." Voyant Tools. 2016. Web. 31 Oct 2016. <http://voyant-tools.org>.

---. "Links." Voyant Tools. 2016. Web. 31 Oct 2016. <http://voyant-tools.org>.