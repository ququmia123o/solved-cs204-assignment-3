Download Link: https://assignmentchef.com/product/solved-cs204-assignment-3
<br>
<ol>

 <li>In the IPv4 addressing format, the number of networks allowed under Class C addresses is _____________</li>

 <li>The network 198.78.41.0 is a _____________</li>

</ol>

(a) Class A network        (b) Class B network

<ul>

 <li>Class C network</li>

 <li>Class D network</li>

</ul>




<ol start="3">

 <li>In a classful addressing, first three bits in Class C IP address is __________</li>

</ol>







<strong><em>Subnetting</em></strong><em>: </em><strong><em>Subnetting</em></strong><em> is the practice of dividing a network into two or more smaller networks. </em><em> </em>

<em>To understand subnetting, please go through the links given below: </em>

<a href="https://study-ccna.com/subnetting-explained/">https://study</a><a href="https://study-ccna.com/subnetting-explained/">–</a><a href="https://study-ccna.com/subnetting-explained/">ccna.com/subnetting</a><a href="https://study-ccna.com/subnetting-explained/">–</a><a href="https://study-ccna.com/subnetting-explained/">explained/</a>




<em>Subnetting is done with the help of subnet mask as explained in here: </em>

<a href="https://study-ccna.com/subnet-mask/">https://study</a><a href="https://study-ccna.com/subnet-mask/">–</a><a href="https://study-ccna.com/subnet-mask/">ccna.com/subnet</a><a href="https://study-ccna.com/subnet-mask/">–</a><a href="https://study-ccna.com/subnet-mask/">mask/</a> <a href="https://study-ccna.com/create-subnets/">https://study</a><a href="https://study-ccna.com/create-subnets/">–</a><a href="https://study-ccna.com/create-subnets/">ccna.com/create</a><a href="https://study-ccna.com/create-subnets/">–</a><a href="https://study-ccna.com/create-subnets/">subnets/</a>

<strong><em>CIDR (Classless inter-domain routing)</em></strong><em> is a method of public IP address assignment which tackles the problem of IP address exhaustion problem (i.e., more networks and computers than the number of IP addresses available). It uses <strong>subnetting and supernetting</strong> principle for efficient allocation of IP addresses to computers. </em>

<a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">https://study</a><a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">–</a><a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">ccna.com/cidr</a><a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">–</a><a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">classless</a><a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">–</a><a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">inter</a><a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">–</a><a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">domain</a><a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">–</a><a href="https://study-ccna.com/cidr-classless-inter-domain-routing/">routing/</a> <a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">https://www.ionos.com/digitalguide/server/know</a><a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">–</a><a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">how/cidr</a><a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">–</a><a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">classless</a><a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">–</a><a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">inter</a><a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">–</a><a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">domain</a><a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">–</a><a href="https://www.ionos.com/digitalguide/server/know-how/cidr-classless-inter-domain-routing/">routing/</a>







<ol start="4">

 <li>If a class B network on the Internet has a subnet mask of 255.255.248.0, what is the maximum number of hosts per subnet?</li>

 <li>(Multiple Choice Question) The subnet mask for a particular network is 255.255.31.0 Which of the following pairs of IP addresses could belong to this network?</li>

</ol>

<ul>

 <li>57.88.62 and 172.56.87.233</li>

 <li>35.28.2 and 10.35.29.4</li>

 <li>203.31.87 and 191.234.31.88</li>

 <li>8.129.43 and 128.8.161.55</li>

</ul>




<ol start="6">

 <li>In a class B subnet, we know the IP address of one host and the mask as given below:</li>

</ol>

IP address: 125.134.112.66

Mask: 255.255.224.0

What is the first address (Network address)?




<ol start="7">

 <li>The broadcast address for IP network 172.16.0.0 with subnet mask 255.255.0.0 is _____________</li>

</ol>




<ol start="8">

 <li>Consider the graph given below:</li>

</ol>







<ul>

 <li>In the above graph, nodes represent the routers, and edges represent the link costs between the routers.</li>

 <li>Apply Distance Vector Routing on the above graph, and determine the shortest path between every pair of nodes.</li>

 <li>Initially every router/node will build its own routing table based on the link cost value of its adjacent neighbors.</li>

 <li>In each iteration, every node will then subsequently share the distance vectors to its neighbors, who will update their own routing table based on Bellman-Ford Distance update equation (dx(y) = min (cost(x,v)+dv(y) for all v). This process continues till convergence is achieved.</li>

</ul>




<strong>Your Task: </strong>Show the contents of the routing table initially for all the nodes, and update the routing table accordingly as mentioned in each iteration. The number of iterations ideally should be equal to the number of nodes present in the graph, after which convergence is achieved. Finally, show the contents of the routing table corresponding to every node.

Based on the output of the algorithm, write down the shortest path between every pair of nodes in the graph using the values in the routing table.




A typical routing table will consist of 3 entries primarily: Destination Node name, Distance, Next Hop Name.

For example, initially, routing table for node A is:

<table width="623">

 <tbody>

  <tr>

   <td width="208">Destination</td>

   <td width="208">Distance Value (which is the link cost value)</td>

   <td width="208">Next Hop</td>

  </tr>

  <tr>

   <td width="208">A</td>

   <td width="208">0</td>

   <td width="208">A</td>

  </tr>

  <tr>

   <td width="208">B</td>

   <td width="208">4</td>

   <td width="208">B</td>

  </tr>

  <tr>

   <td width="208">C</td>

   <td width="208">Infinity</td>

   <td width="208">–</td>

  </tr>

  <tr>

   <td width="208">D</td>

   <td width="208">Infinity</td>

   <td width="208">–</td>

  </tr>

  <tr>

   <td width="208">E</td>

   <td width="208">Infinity</td>

   <td width="208">–</td>

  </tr>

 </tbody>

</table>







Routing Table for B is:

<table width="623">

 <tbody>

  <tr>

   <td width="208">Destination</td>

   <td width="208">Distance Value (which is the link cost value)</td>

   <td width="208">Next Hop</td>

  </tr>

  <tr>

   <td width="208">A</td>

   <td width="208">4</td>

   <td width="208">A</td>

  </tr>

  <tr>

   <td width="208">B</td>

   <td width="208">0</td>

   <td width="208">B</td>

  </tr>

  <tr>

   <td width="208">C</td>

   <td width="208">1</td>

   <td width="208">C</td>

  </tr>

  <tr>

   <td width="208">D</td>

   <td width="208">Infinity</td>

   <td width="208">–</td>

  </tr>

  <tr>

   <td width="208">E</td>

   <td width="208">5</td>

   <td width="208">E</td>

  </tr>

 </tbody>

</table>










<ol start="9">

 <li><strong>Link State Routing:</strong></li>

</ol>

Consider the graph shown below:










<ol>

 <li>Apply Dijkstra’s algorithm, and determine the shortest path between:</li>

</ol>

(a)  node A and node E (b) Node A and node D

<ol start="2">

 <li>What is the time complexity of Dijkstra’s algorithm? Explain how you obtained the above answer? Can we do better, how to do so and what will be the lowest time complexity in such a case?</li>

</ol>

3