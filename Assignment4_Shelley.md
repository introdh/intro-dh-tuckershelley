# Writeup
For this project I made a network of connections between supreme court cases. Each node is a specific court case and the edges represent references to a different case. I chose cases from three different topics of court cases to see if they were often cited by the other cases. The three topics I chose were involuntary confession, desegregation, and due process: prisoners rights and defendents rights. I figured that there would be a lot of connections between involuntary confession and prisoners and defendents rights as their rights would be violated in the process of a forced confession. I also wanted to look at race and see if there were many connections between desegregation issues and these two topics. Below is an image of the issues each color coded in the network that I created. By looking at this network it makes the argument that the overlap of citations is much more abundant between involuntary confessions and desegregation, leaving out prisoners and defendents rights. I thought the rights of African Americans would be violated often, especially in relation to desegregation cases, however the network says differently. The network infers that many African Americans were often advised by attourneys to plead guilty due to their inability to win the case due to their race. 

![alt text](https://github.com/introdh/intro-dh-tuckershelley/blob/master/Issues.png "Issues")

As you can see here, aside from a few cases, most of these don't have very much overlap with each other. However, if you look at this next photo, you can tell that there are five different clusters of cases that are involved with eachother. In this network, the green cluster are almost all desegregation cases that often get cited by involuntary confession cases. I took a closer look at the upper left most case in that cluster to see why it is cited so often by involuntary confession cases. This case involved a group of African Americans that refused to leave a golf course after being asked to leave. The jury was told that the reason they weren't allowed on the course in the first place cannot be due to their race. However, they were found guilty regardless (justia.com, 364 US 177). 

![alt text](https://github.com/introdh/intro-dh-tuckershelley/blob/master/Cluster.png "Clusters")

Centrality is very telling on the implications that certain cases leave for others. Centrality is a measure of which nodes have the most edges stemming from them. In this example, it is the court case that gets cited the most by the others in the network. It is clear that the centrality lies in the topic of involuntary confessions. The Eigen score is a measure of the ratio of its edges compared to the central node. The central node is 360 US 315. It is a case that involved the involuntary confession of a man due to a violation of due process and his rights (justia.com, 360 US 315). It is rather intuitive that this case should be the center node as it refers to all the topics in this network. 

![alt text](https://github.com/introdh/intro-dh-tuckershelley/blob/master/Centrality.png "Centrality")

While this network sheds light on the relationship between the three court case topics, it has some drawbacks that decrease the effectiveness of it. The first is that, as Franco Moretti states in his network of Hamlet dialogue, there is no weight of how strong the connection is (Moretti, 3). This hurts the impact of the network as it doesn't show how important or weighty the citation was. Some of them might have been very small parts of the court arguments while others may have changed the tide of that trial. Another issue is that I have constructed no sense of directionality with these edges. In other words, there is no sense of whether a node, or case, is being cited or is doing the citing. This can really throw us off when looking at centrality because it could either be a case that is cited a lot or a case that pulled from many different places. 

We could also go further with this network. One way I was thinking, is to color code the nodes in which the cases involved an African American descendent. This would be similar to the NIH funding profile network from the Weingart reading (Weingart). 

In conclusion, this network gives us a glimpse into the relationships between Supreme Court cases regarding desegregation, involuntary confession, and due process: prisoners and defendents rights. There are some drawbacks that don't allow us to make assumptions about the data, but a lot can be learned by teasing apart the network and even more can be done with it using different technologies.

# Bibliography

Moretti, Franco. "Network Theory, Plot Analysis."

Weingart, Scott. “Contextualizing networks with maps.”
