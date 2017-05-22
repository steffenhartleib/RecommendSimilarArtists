# A down and dirty recommendation script for a daily deal music site. 

The merchandizing team of a daily deal website was curating daily deal offers of records by a specific artist.
<br/> 
<br/> 
The merchandizers wanted to know which additional artists they should upsell in the shopping cart. (They were running a proprietary platform where product recommendations
had to be set manually...)
<br/> 
<br/> 
I wrote a simple script that takes as input a list of featured artist and returns for each one a list of the 10 most similar artist. 
<br/> 
<br/> 
Similarity is calclulated as the probability that customers would buy the recommended artists, given that they had also bought the featured artist.
