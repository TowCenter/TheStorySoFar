Initial conversion mostly manual. Will see how other elements go. 

First pandoc to html:
pandoc TheStorySoFar.tex -o The StorySoFar.html

	* run it through the RightRail script, which also generates _web.html, with revised header "span" tag

Then pandoc to md:
pandoc TheStorySoFar.tex -o The StorySoFar.md

	*manual regex editing of all footnotes refs to "endnotes" since we can't do in-page anchors in GitBook anyway. Regex (SublimeText) search: (endnotes)(.*)(\)) replace: endnotes)






