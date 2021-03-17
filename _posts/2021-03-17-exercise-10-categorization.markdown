---
layout: post
title:  "Exercise 10 - Categorization"
date:   2021-03-17 03:13:13 -0500
categories: 
---

# Categorization with Wikidata

## Get data from Wikidata

My corpus is issues of the classics journal *Classical Quarterly*. I know that most major journals have a wikipedia page, so I was curious to see what journals I could turn up in a wikidata query for journals in classics. I searched "instance of > academic journal" and "main subject > classics" but this only returned two results: *Transactions of the American Philological Association* and *Mouseion*. I played around with both statements, but I quickly found that this would not work because the categorization was not consistent. I searched for the wikidata pages for various journals (*Classical World, Classical Journal, Classical Quarterly, AJA, Hesperia*) to try to find some standard categorization but there was no consistency in how these were categorized. For example, classics journals could be categorized as "academic journal", "history journal", "periodical", etc. Some journals did not have any other specific categorization to narrow to classics and the next most specific category was "title" or "date", which obviously would not work for a broad search like I wanted to do. When I did try to specify these searches to classics specific journals, there was also a wide variation of categorization used. I could search for classics as a "major topic" or "academic discipline" or "field of work." I don't know which choice is necessarily best, but there is no clear standardization which makes it difficult to produce more than one or two journals at a time with each variation of the search. Other issues arise, like classical philological and archaeological journals being categorized as "philology" and "archaeology" but no more specific than that. 

## Give data to Wikidata

I added the statement "main subject > classics" to *Classical Quarterly* and *Classical Journal* wikidata. This seems to be the most common statement used to categorize journals in the field of classics. 