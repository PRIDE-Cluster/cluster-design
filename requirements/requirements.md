###Format

As a warm up for this. Taken from the book “A Practical Guide to Information Architecture” by Donna Spencer. This one is about how people look for information (I have summarized it a bit). We could try to wonder what user stories we have in each category (if any at all).

####Finding known items

The user knows what she/he wants
Has terms to describe it
Knows there is an answer
Knows how to recognize it when it appears

####Exploring

The opposite of finding
The user may have some idea of what is looking for
May or may not know how to articulate it

####Discovering

I was looking for that.. and I found this (that I’m interested in btw)

####Comparing

Comparing different results

####Getting a broad idea

Getting a global idea of the information contained in the resource


We don’t need to fill up each category or anything like that. I just think this is a good starting point for finding our user’s needs for information.

###Clinical Researcher
(I’ll try to stick to the categories, since I think they’re quite good)

####Finding known items

Searching for the signature proteins of certain cell types (B-cells for example are characterised by CD20 and CD19) in experiments. The question would be who identified B-cells in their samples
I’m reading about new potential biomarkers in a certain disease (f.e. Il-6, TNF-alpha) and want to see who identified them in their samples. I also want to have quick access to the corresponding publications. Additionally, I, of course, need to know how reliable these identifications are. 

####Exploring

I’m working in the field of melanoma research. First of all, I want to see what kind of samples are available in PRIDE and how submitted them (we generally know a few of the groups, and know whether we trust them or not). Again, the link to the publications is essential.
Now I want to explore what kind of proteins these people identified in their samples. Ideally, I’d be able to limit these lists to a certain set of proteins of interest.

####Discovering

I might be interested in a certain melanoma cell line. I’d like some easy way to browse through the available samples in PRIDE (f.e. a tree structure like Human > skin > melanoma > A320 (the name of the cell line). While doing this, I can’t find the A320 cell line but I see that a different cell line is also available. Now I’m interested what the people found there.

####Comparing

I’ve found two projects I’m interested in, a cell line and a human sample. Now I’m asking myself whether the same signature (inflammation through IL-6 - the list would be about 10-20 proteins) was identified in both samples.
Additionally, I’m interested in how similar two projects that both analysed A320 cells (a cell line) are to each other. What proteins to they share, which proteins were only identified in one of the two.

####Getting a broad idea

In my story this overlaps with “Discovering”. I want a tool that quickly tells me what kind of f.e. disease models are present in the resource. If I then navigate to a project, I want to know how many proteins are identified, and how many of these are reliable. Again, I always want a direct link to the publication since this will often be my primary method to assess a dataset’s quality.


###Proposed requirements for MS proteomics scientist and bioinformatician
(Here I focus on peptides)

####Finding known items

Searching for one/multiple peptide sequences to see what have been observed before, in which quality they have been observed.  
If I only know the peptide mass, I would like to see which peptides have been identified and in which quality.
JG: I would like to limit the searches by (at least) species, if possible even tissue (but this information is scarce, it could be retrieve through GO annotations)

####Exploring

It would be nice to search by peptide mass by dalton with a tolerance (ppm)
It would be nice to see and filter by the quality of the peptide identification.
It would be nice to see and filter by species so that I can target a particular or a group of species.
It would be nice to see and filter by modifications so I can target a particular or a group of modifications.
It would be nice to have a simple method to quickly select common labelling techniques (ie iTRAQ with mod on ?Y, n-term and K)
It would be nice to be able to consider ambiguity amino acid existing in peptides, including I/L and K/Q
It would be nice see and filter by peptide sequence matching types (exact or contains)

####Discovering

Investigating further a particular peptide identification, I would like find out in which state this peptide was identified. e.g. mass, protease, modifications, charge states, start, stop, protein accessions , protein databases, uniqueness.
I would like find out what are the species this particular peptides have been observed. 
I would like to find out the projects this peptide has been seen alongside the project metadata, such as: publication.

####Comparing


####Getting a broad idea

Need a tool to help me quickly validate a peptide or a potential peptide identification, also provide me with a quality measure. 

####Comparing/Discovering/Broad idea?

Jose: when browsing search results, it would be nice to have a visual representation of them, where I can grasp where and how my results are located in the search space. I would be able to see things such as how common is my peptide, how big is the cluster it falls in with respect to other clusters, the quality of the results, and other metadata. This is a lot of information and a visual representation will help me to digest it. Ideally, visual patterns will emerge from search results in a way that once I get familiar with the representation, I will quickly understand the nature of my discoveries.
