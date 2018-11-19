#### Luke Malcynsky
#### Dr. Tilton
#### Intro to Digital Humanities
#### Assignment 2: *Networks*
#### November, 2018



Within the realm of the digital humanities, networks are experiencing quite the awakening; which Weingart (2012) attributes, in part, to the newly available, easy accessible resources for acquiring datasets and tools for building networks. The term “network” refers to any complex, interlocking system (Weingart, 2012). A network, in its simplest form, is a collection of points joined together in pairs by lines; these “points” are called *nodes*, while the “lines” are known as *edges* (Newman, 2010). A network can be a useful tool for analysis, as it provides a visual representation of complex relationships within a corpus. In a network, the relation between two nodes is represented by the edge connecting them, and the *degree* of a node refers to the number of edges connected to that node. As networks are used to analyze relationships within a corpus, it is important that when selecting a corpus, the nodes must be interdependent for “representing information as a network implicitly suggests not only that connections matter, but that they are *required* to understand whatever’s going on” (Weingart, 2012).


The corpus used to build the following networks is comprised of data from U.S. supreme court cases. The goal of developing networks of this data was to analyze the relationship between court cases and a specific area of law, by creating a visual representation of a citation network. In order to select an area of law to examine, a code book, developed at Washington University-St. Louis, was used to identify what cases addressed which areas of law. I decided to focus on an area titled “Copyright and Patent Law”. I selected two cases, “Patents and copyrights: Patent” (80180) and “Patents and copyrights: copyright”, as the fact that they shared a categorization suggested that they were interdependent -- therefore suggesting their relationship would be successfully represented through a network. Several bimodal citation networks were developed, in which the nodes represent specific supreme court cases while two cases (nodes) are connected by an edge if five or more cases cite those two cases together; as to insure the network would not overrepresent cases that merely include a lot of citations. Several variations of the network were developed, using different color coding of the nodes in order to convey different information about the corpus (Fowler and Jean, 2008).


The first citation network that was built, “Plot issue”, describes which area of law, copyright (red) or patents (blue), each case in the network coincides with. This visualization illustrates that many cases within this network are interconnected despite pertaining to different issues. The next network developed, “Plot year”, shows a citation network color coded by date. With this added element, one can examine any recent case (node) within the network and see how it can be traced back to fundamental (patent) cases from the 1950s. The third network developed, “Plot vote”, provides important facts about the corpus, as it shows the number of dissenting votes on each case. This information is significant as it highlights which cases were controversial, such as the case labeled on the network below. This network shows a wide range of numbers, particularly cases with zero and four dissenting votes, indicating that cases or issues in the realm of copyright, patent law are not always black and white; there seems to be no pattern in dissenting votes.


![Issue(label)](https://github.com/introdh/intro-dh2018-Lmalcynsky/blob/master/images/Issue(label).png)


![Year(label)](https://github.com/introdh/intro-dh2018-Lmalcynsky/blob/master/images/Year(label).png)


![Vote(label)](https://github.com/introdh/intro-dh2018-Lmalcynsky/blob/master/images/Vote(label).png)


“Plot cluster” provides a visual of the communities of cases within the citation network. For example, as shown on the graph below, the two purple nodes belong to a distinct community that is rather isolated from others within network. This cluster contains two cases: *F. W. Woolworth Co. v. Contemporary Arts, Inc.* (1952) and *Feltner v. Columbia Pictures Television, Inc.* (1998). While each node in the network is titled, an understanding of the scope of each case is required in order to comprehend what each communities is associated with. With regards to the purple community, additional research revealed that both cases involve copyright infringement relating to works of art (Wikipedia, October 2018; Wikipedia, July 2018). 


![Cluster(label)](https://github.com/introdh/intro-dh2018-Lmalcynsky/blob/master/images/Cluster%20(label).png)


“Plot Gatekeepers” highlights which cases act as key transition points within the citation network; moreover, which cases link together the different communities identified in “Plot cluster”. One significant gatekeeper is highlighted on the graph below: *Diamond v. Chakrabarty* (1980). Further research revealed the obscure scope of this case, which involved  the question of whether genetically modified organisms can be patented (Wikipedia, September 2018). Despite the peculiar scope of this case, within the network it serves as a critical liaison between the several fundamental patent cases from the 1950s (labeled in “Plot Year” and “Plot Issue”) and more recent patent cases; ultimately connecting those fundamental cases the main body of the network.      


![Gatekeeper(label)](https://github.com/introdh/intro-dh2018-Lmalcynsky/blob/master/images/Gatekeeper(label).png)


As Lastly, in the “Plot Centrality” graph, each node is color coded based on degree, therefore underlining which cases are cited the most (by other cases). Ultimately, this graph points to which cases (or decisions) were most significant, or central, to the citation network, and to the sphere of U.S. Copyright and Patent Law as a whole.

![Centrality(label)](https://github.com/introdh/intro-dh2018-Lmalcynsky/blob/master/images/Centrality(label).png)


While there are numerous possibilities of network analysis, as with any method, there are several limits as well. As exhibited by the citation networks above, network analysis can be a useful tool for conducting research, as it can identify, or at least clarify, complex relationships within a corpus -- information that is often difficult to convey by other means. However, it is important to note that network analysis is not a successful method for approaching subjects that are not interdependent (Weingart, 2012). Furthermore, the relationship between some interdependent subjects are so complex or irregular that they are best not represented through a network, as the graph may be difficult to read. Another known limitation of network analysis method is the graphs’ tendency to portray data in a manner that flattens time; although, in the network analysis of the Supreme Court data, “Plot year” was generated so that such information was not excluded from the process of analysis. As shown through the network analysis of “Copyright and Patent Law” U.S. Supreme Court cases, the results of this method potentially highlight new, or interesting information about a corpus. On the other hand, networks stand pooly alone, for additional and extensive research is needed in order to contextualize the results before informed conclusions about the data can be drawn. Simply, a sufficient understanding of each node in a network is necessary to comprehend the significance of the connections between them.


#### Works Cited


* Fowler, James H, and Jeon, Sangick. “The Authority of the Supreme Court Precedent.” *Science Direct, Elsevier*, Social Networks, 2008.


* Newman, Mark E. J. “Networks: An Introduction.” *Oxford Scholarship Online*, Sept. 2010.


* Weingart, Scott B. “Demystifying Networks, Parts I & II.” *Journal of Digital Humanities*, PressForward, Mar. 2012


* “Diamond v. Chakrabarty.” *Wikipedia*, Wikimedia Foundation, 4 Sept. 2018



* “Feltner v. Columbia Pictures Television, Inc.” *Wikipedia*, Wikimedia Foundation, 15 Oct. 2018


* “F. W. Woolworth Co. v. Contemporary Arts, Inc.” *Wikipedia*, Wikimedia Foundation, 27 July 2018






