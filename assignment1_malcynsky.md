#### Luke Malcynsky 
#### Dr. Tilton
#### Intro to Digital Humanities 
#### Assignment 1: *Topic Modeling* 
#### October, 2018



Advances in technology over the past thirty years have dramatically changed the conditions in the field of the humanities. This change was fueled by the unprecedented new access through computers and the internet. Massive digital libraries, such as Jstor, have provided scholars with the opportunity to obtain large collections of texts (corpus), opening the door for text analysis on a large scale. Macroanalysis, or “distant reading”, is an approach for highlighting broad scale trends, i.e. patterns within a large body of text (Brett, 2012; Goldstone & Underwood, 2012).  
   
   
Topic modeling is a popular method of macroanalysis. The process of topic modeling is rooted in mathematics, involving complicated algorithms that require the processing power of a computer. In order to run a topic model on a corpus, it must be converted into a format (txt) compatible with one of several computer programs that can run topic model tools. Many of these programs impliment latent Dirichlet allocation, or LDA, in order to transform a set of “free” data into “structured” data. LDA is the basis of MALLET, an open source topic model tool that seems to be a favorite amongst scholars in the realm of the digital humanities (Brett, 2012). Topic model tools like MALLET scan through each document in a corpus, sorting words into groups based on co-occurrence and prevalence throughout the entirety of a corpus; these groups are called topics. Topics are most simply described as “a pattern of co-occurring words” (Goldstone & Underwood, 2012). Topic models have the potential to provide many different insights into a corpus. In a well-executed topic model, topics often underline a reoccuring focus or theme of a corpus, or a change in such. Furthermore, topics may highlight other patterns within a corpus, such as a particular critical approach or a rhetorical strategy.
    
    
The Annals of the American Academy of Political and Social Science (AAAPSS) is “a policy and scientific journal in political and social science”. From its first publication in 1890, the journal has been dedicated to strengthening the communication between “scientific thought and practical effort”. The journal aims to foster important questions in the fields of social and political science, as well as to promote research that addresses important issues relevant to those fields. These efforts have garnered the AAAPSS a reputation for refusing to avoid difficult topics. (Wikipedia, 2018) 
    
    
The Annals of the American Academy of Political and Social Science has been releasing publications for one-hundred and twenty-eight years, six issues annually. The quantity of data available on AAAPSS makes it an ideal subject to topic model. By utilizing a topic model to analyze the articles published from 1920-1975 in The Annals of the American Academy of Political and Social Science, one can obtain valuable insight into what subjects were the most pressing or controversial in the fields of social and political science, and how those subjects are related. 
    
    
The text data from this journal was obtained through the online database JSTOR — JSTOR is an expansive digital library which provides scholars, researchers and students with access to more than twelve-million academic journal articles, books and primary sources across seventy-five disciplines (JSTOR, 2018). While some content on the site is public domain, most access to this database is by subscription (most often, as in the case of this model, through a university or institution). Databases such as JSTOR are essential to text-mining methods such as topic modeling, as they allow users to request and download massive collections of text in a variety of formats. 
    
    
The AAAPSS journal articles downloaded from the JSTOR database were published from 1920 to 1975, the entire data set (1890-2018) was too large to download through a single request. Additionally, when topic modeling, selecting data from a specific time period makes it easier to contextualize topics. This particular period was selected as that many significant events and progressive changes with the realms of modern social and political science occurred within this window of time.
    
    
Once JSTOR had received and processed the request for the articles, the data was accessed via a hyperlinked zip-file, which then was downloaded and decompressed into a format compatible with RStudio. RStudio is a free, integrated development environment (IDE) for R, an open-source programming language for statistical computing and graphics (RStudio, 2018). Within the Rstudio interface, a function was utilized to convert the data from .xml to .txt files, so that it then could be processed through the provided code to generate the data needed to build a topic model. Subsequently, this data was entered into a function that generated a topic model with “k” number of topics. An additional function was used to build instructions for a visual representation of the topic model, and ultimately of the corpus, which was then published as an open-source web-page via Github.
    
    
The last two steps of this process were repeated several times in order to determine what number of topics proved to form the most successful model of the corpus. A model with twenty-five topics was generated as a baseline, proving that this number of topics was too large, as it was clear many topics could be consolidated. Models with ten and twelve topics were then tested, both resulting in broad, muddy topics that did not provide enough insight into the corpus. It was ultimately determined that fifteen was the most successful number of topics to model the corpus. As shown on the web page linked [here](https://lmalcynsky.github.io/dh-topic-models/#/model) (as well as below), each topic in this model is clear and distinct; within each topic, there is a clear relationship between each listed term, and the titles of articles included all seem to coincide with a specific theme. 
          
https://lmalcynsky.github.io/dh-topic-models/#/model
    
    
The topics displayed in this model illustrate key concepts of the corpus, as well as in the realms of political and social science, some of which were expected; such as “Academics” (I and II), “Politics”, “Law”, and “Economics”.  However, several topics were unexpected. For a journal that may appear to have a national scope, international relations is clearly relevant subject throughout the corpus. This is primarily illustrated through two topics in the model. 
    
    
The first topic, “Communism and the East” provides insight into a recurring focus in the journal on communism in nations such as China and Soviet union as a significant issue. Ultimately, this topic illustrates an important theme of the corpus: national anxieties towards the East perpetuated through political, cultural differences and the cold war. This topic is also particularly interesting because these geographies are still very relevant focusses or concerns in current American politics. Through further research into the articles listed under the topic, “Communism and the East”, one may gain a better understanding of historical factors contributing to the United States current relationship with nations such as China and Russia. 
    
    
Second, the topic titled, “Trade, Migration and Europe”, illustrates another, but very different, focus on international affairs within the corpus. As shown by the grouping of articles within the topic, international trade, particularly tariffs, is a very significant subject within this journal. Topic modeling, then, helped identify expected and unexpected subjects relevant to the corpus.  


Topic modeling is a good method of discovery; however, additional research and contextualization is needed in order to make conclusions about what may be highlighted by a topic in a topic model. Some scholars disagree with this form of text analysis based on the idea that a process like topic modeling removes what is human from the study of the humanities. However, in many ways, the results of topic modeling are more valuable because they were produced by a computer and not a human. First, the broad scale analysis of large a corpus is only possible due to the superior processing power of computers (Brett, 2012). Second, “topic modeling gives us a chance to bracket our received assumptions about the connections between concepts,” as the program that formulates each topic is free from preconceived bias and other human notions that can pollute scholarship (Goldstone & Underwood, 2012). While there are limitations to topic modeling, this method certainly holds the potential to be successful and informative tool for macroanalysis.  By utilizing a topic model to analyze the articles published from 1920-1975 in The Annals of the American Academy of Political and Social Science, one can obtain valuable insight into what subjects were the most pressing or controversial in the fields of social and political science, and how those subjects are related. 


#### Works Cited


* “About.”*RStudio*, RStudio, 6 Oct. 2018
* “About JSTOR.” *JSTOR*, ITHAKA, 2018
* “American Academy of Political and Social Science.” *Wikipedia*, Wikimedia Foundation, 5 July 2018
* Brett, Megan R. “Topic Modeling: A Basic Introduction.” *Journal of Digital Humanities*, 12 Dec. 2012
* Goldstone, Andrew, and Ted Underwood. “What Can Topic Models of PMLA Teach Us About the History of Literary Scholarship?” *Journal of Digital Humanities*, 14 Dec. 2012

