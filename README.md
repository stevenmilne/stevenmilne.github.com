# stevenmilne.github.com
Experiments.

## This is the code for http://northernlightsconf.co.uk
This is pushed to github.io so is a static website that uses page includes to enable dynamic pages to avoid code repetition.

## Site structure
folders with _<name> can be used as page includes
index.html - points to homepage under layouts folder that is to be used with jekyll syntax.
You'll notice that you can call adjacent pages with <a href="/codeofconduct/">code of conduct</a> from sponsorship.html. 
_includes folder - holds a number of components that are called by homepage and others to cover scheduler, sponsors, speakers, and usual headers and footers.
_includes/footer.html - lists names of organisers and other repeated info.
_includes/head.html - has stlying for each page
_includes/header.html - has top menu for the site

_speakers folder - holds a markdown file for each speaker that is called by the loop in _includes/speakers.html file

These are the main parts you need to know. 

## Setting up the files for a new event
Go and change main files mentioned above to modify date, speakers, and change sponsorship and ticket prices accordingly to suit the team's goals.

