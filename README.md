THis porject takes periodicals and generates some statistics such as # of articles per issue, article length, sentence length, and really antything else fun. Thes shows the historic trends, issue to issue or periodcal to periodical etc usign d3.


1) Get Data source
2) Parse Data source
3) Display Data



Geting the data source seems tricky since some periodicals are not free.

Initially wanted to do the economist and the new yorker.

Maybe use online free periodicals and throw in markers for google search changes. The question is how do Google search algorithm changes affect the content created by online publications.

Online news sources
MyBankTracker
Verge
BuzzFeed


Start with just new york times and use the Wayback archive
Check daily at noon:
Number of stories
Length of each story heading
Lenght of each story
# of words in each story
# of words per sentence in each story
# of links in story text
Reading level of story text
# of images?
# Headline Length


December 3rd, 2014
NY Times
Homepage
	article.story data-story-id=id#
	h2.story-heading
		a contains actual h2 text
	p.summary
Article Page
	Headline
		h1#story-heading.story-heading itemprop="headline"
	Story
		div#story-body.story-body
			classes p.story-body-text.sotry-content


This seems to not be the case for earlier versions of the site.

