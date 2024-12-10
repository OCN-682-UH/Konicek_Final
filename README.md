# Konicek_Final
Konicek OCN682 Independent Project
date: "2024/12/10"

This repository is for my final project. 
I decided to grapple with some of my microbiome data in order to make some decent figures in R.  

So far in my life, I was very unable to do that.

However, this class has helped so much. 

I feel much more confident navigating R and code that I have scrabbled together to make microbiome plots.  

# The Story 
The story I want to tell with this data is that Hawaiian picture-wing flies are very cool, and some species are endangered.  
We can breed and rear some of those species in the lab. 

If we wanted to, say, reintroduce lab-reared flies to the wild, what would that do to their microbiomes? 


Releasing lab-reared flies into the wild could affect their microbiome, and as a result, the functioning/health of the fly. 


We got permission to take some endangered lab flies, mark them, release half of them into the wild and keep half of them in the lab. 
After three weeks, I went and collected some previously released flies (it was hard to find them but I did it!). 

We checked out their microbiome composition using amplicon HTS. Here, I'm working with our ITS (Fungal) data.

Based on the sequence depth histogram, it looks like all the samples sequenced decently, although they maybe shouldn't be compared to one another without transforming data. 
The relative abundance plot shows a big difference in taxa richness when you compare lab-raised flies to rewilded flies! 
Finally, the beta diversity PCoA shows how distinct the sample type communities are from one another, but how similar samples from the same sample type (lab-reared or rewilded) are.

# Contents of Repository 

_Data_. 

1. OTU matrix as output by Mother (.shared)
2. taxonomy table that corresonds to OTU matrix, output by Mother (.taxonomy)
3. metadata file for samples (.csv)
4. data dictionary (.csv)

_Scripts_.  

I tried my little grubby hands at a **xaringan**. 
There is a markdown file, an html file, and a file of photos for the presentation.
It was NOT AS EASY as blasting out a powerpoint! 
But I am glad I tried. I am a little worried I should have stuck all my photos in the data folder, but this made the easiest path to the **xaringan**. 

_Output_. 

There are three .png plots. beta1-1.png is a beta diversity PCoA plot I made using my microbiome data. depth-1.png is a histogram of my sequence reads per sample. relabnd-1.png is a relative abundance bar plot per sample for the top 10 genera (plus taxa that have an "Unknown" genus.). 

Ok. I think that is all. I hope this is helpful. 