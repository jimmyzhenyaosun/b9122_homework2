# b9122_homework2
 Creating repository for CBR hw2
 Author: Zhenyao Sun

Write web crawlers for the following two tasks:

webcrawler_UN.ipynb

1.Extract at least 10 United Nations press releases containing the word “crisis”. Start with the 
following seed url: https://press.un.org/en. Notice how press release pages have the “PRESS 
RELEASE” relative link in the top left corner. Here is an example press release:
https://press.un.org/en/2023/sc15431.doc.htm where the “PRESS RELEASE” has the following 
relative anchor tag: 
<a href="/en/press-release" hreflang="en">Press Release</a>
Use this information to determine whether the web page is a press release. 

webcrawler_EU.ipynb

2.Crawl the press room of the European Parliament and extract at least 10 press releases that cover 
the plenary sessions and contain the word “crisis”. Start with the following seed url:
https://www.europarl.europa.eu/news/en/press-room
Notice how press releases related to plenary sessions contain the text “PLENARY SESSIONS”
with the following html:
<span class="ep_name">Plenary session</span>

Both webcrawler will extract url and generate files with html content.
in the format of {part_num}_{url_num}.txt