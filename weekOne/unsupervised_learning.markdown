
#Unsupervised Learning

- Can we find categories existing within the data?
	- Clustering algorithms	
	- Used by news.google.com >groups cohesive news stories

- Used in genomics 
	- Measure how much a certain gene is expressed.
	- Run a clustering algorithm to group individuals into different types
	
We don't know the data, but can we find information about it without knowing th 'right' answer.

- Used to organize large computer clusters.
	- Try to figure out which computers work together

- Social network analysis.
- Market Segmentation >group customers
- astronomical data analysis

## Cocktail Party Problem

Speaker 1, Speaker 2

Microphone 1, Microphone 2

Speakers talking and microphones are interacting differently based on distance.

'Cocktail Party Algorithm' - Listens to these different microphone recordings and separates out the voices.
	- Used for audio filtration
	- 'Sounds like 2 different audio source and here are the two I found'

#### How complicated is this?
- The algorithm can be done in one line of code

```
[W, s, v] = svd((repmat(sum(x.*x,1), size(x,1),1).*x)*x');
```
svd -> single value decomposition
	- This would take many lines of code in java/python but Octave has it implemented already. 

If you use octave you can learn quicker. Prototyping is used in Octave.

'Trust me on this one' - Andrew Ng 



```






