---
layout: page
title: Corpus Dictionary
permalink: /Corpus-Dictionary/
---
# The Classical Quarterly

* *years*: 1907-1925
* *Number of Volumes*: 19
* *Number of Words*: 5251

## Data Dictionary 

### Divisions

* Front Matter
* Index
* Issue (no1-4)
* Section (further divided below)

### Sections

* Articles
* Reviews
* Summaries of Periodicals

### Symbols/notation used:
* `@new-page` and `@` bracket page breaks
* `@page-header` and `@` bracket page headers such as article title, author name, and page number
* `@article-title` marks the title of each article
* `@issue-title` marks the title of each issue 
* `@start-article@` and `@end-article@` brackets each article body
* `@article-author` marks the author's name of the article
* `!!start-articles!!` and `!!end-articles!!` brackets the articles and reviews section of each issue
* `!!start-summaries-of-periodicals!!` and `!!end-summaries-of-periodicals!!` brackets summaries of periodicals section

## Goals
* clearly demarcate sections of the issues - articles, reviews, summaries of periodicals.
* mark footnotes - bracket with a notation that will allow for easy removal. I don't want to remove them entirely, but want the ease of removing for using certain programs.
* Learn the the more complex regex syntax, this will make cleaning more efficient and my regexes more universal across issues/volumes.
* Fix OCR table issues
  * FineReader was great but I hit my download limit immediately for the trial. Depending on the volume of the problem, I may be able to copy and paste individual pages.
  * For now, some tables might be better off bracketed with a notation and removed when running plain text through certain programs.
* bracket off tables - decide what counts as a table and then mark these off as necessary
* solve the line break issue
* Clean up text itself 
	* have yet to identify any major issues in OCR that aren't Greek letters or symbols that have no text equivalent.
