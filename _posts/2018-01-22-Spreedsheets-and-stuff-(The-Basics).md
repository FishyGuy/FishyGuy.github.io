---
title: Spreedsheets and stuff (The Basics)
layout: post
author: aaron.litvin
permalink: /spreedsheets-and-stuff-(the-basics)/
source-id: 1EnOAh-jBbT3BJlHMF8iDXeFy-YwlGir4bkSkFqPq3dQ
published: true
---
<table>
  <tr>
    <td>In IT, we're learning how to work with spreadsheets.
</td>
  </tr>
</table>


<table>
  <tr>
    <td>Data validation:
Select boxes to data validate. Then go to the Data tab up top and then select Data Validation and select the area to search from.

</td>
  </tr>
</table>


<table>
  <tr>
    <td>RunningTheStoreAsAMindlessStoreClerkSheepWhoFailedAllTheirUniversityTests

=iferror(vlookup(E2,$A$2:$B$5,2,false), ) <- Command tells spreadsheet that if there is an error in a box, do nothing. Code for pink boxes. The pink displays the price of each item by finding it from the selection of vlookup in columns A and B.

</td>
  </tr>
</table>


![image alt text]({{ site.url }}/public/k0rMRu9USkAJCL41tIcNQ_img_0.png)

<table>
  <tr>
    <td>=If(G6>=(H9),(H7*(1-H8/100)),H7)   <- Code gets discount and gives final price.

If the quantity of items (G6) is more than or equal to the item number required for the sale to take place (H9), then activate the sale. (Rest of code).

Some of the numbers you enter yourself like the discount percentage the number of items required for the sale to work and the quantity. The rest is done and changes automatically based off of what is entered.
</td>
  </tr>
</table>


