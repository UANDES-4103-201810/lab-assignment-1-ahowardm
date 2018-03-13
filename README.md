# lab-assignment-1
Base project for lab assignment 1

##Structure

The structure starts with a html tag and finishes with a html close tag.
### header
The HTML file has a head tag where the meta information and other files are loaded. Including the css stylesheet and the YCombinator icon.
Also the title of the website is defined with the title tag.
### body
The body has 2 tags inside: center and script. The first one is used to center the content nside (in this case the content of the site) and script is used to load a javascript file. The script is at the end so the site doesn't take too much time to load.
Now we go into the center tag where the content of the site is. The main content is defined as a table with the table tag with id "hnmain" (for css to be able to locate it). Later comes a tbody tag where the rows are defined. There is no thead tag in this case.
The menu of the site is defined inside the table as being a row (with the tr tag). Inside the first tr tag there is just one td tag that defined a standard cell. This cell has background color #ff66000. Inside this cell there is another table defined to hold the menu. This second table has no header, just the body defined with the tbody tag. Inside the body there is a tr tag that defines the first row. Inside the first row there is a first cell (td tag) with a link inside (a tag) with the YCombinator logo (img tag). The second cell (second td tag) has inside all the menu, therefore it is grouped inside a span tag. The menu is composed of a tags (links) with their corresponding text and href. The first link is in bold font using the b tag. Outside the span tag there is defined a third cell with a td tag that holds a span with a link (a tag) inside with the login text. Then all open tags are closed to close the table defined to hold the menu.
The first row of the first table is closed and the second row defined with fixed height to have white space. Next the next row of the table is defined. This row has all the news. To hold the news a new table is defined in the first cell of the row of the previous row. This new table has no header, just a body (tbody tag). Every news uses 2 rows for the content followed with a row of class spacer with fixed height.
At the end there is a third row of the outside table to hold the footer. This row has anew table and 2 center tags.

##Source

There are 6 files. The index file holds the structure and content, then there is the javascript file with the scripts. The third one is the CSS stylesheet definitions using CSS selectors and format definitions. The last 3 files are gif files with logos.

##xhr request

The XMLHttpRequest object allows to update the page without having to reload thepage. With this tool, new news can appear without having to reload the page.

##Security

The certificate was issued by COMODO RSA Domain Validation Secure Server CA and expires on August 21 of 2019 at 20:50:59.
