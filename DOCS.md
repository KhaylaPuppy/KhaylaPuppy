# License
Governs the use of the repository, no file extension is needed as per github files.

# Readme
As this repository ends with my username, it becomes my main display repository and readme. yes, the repository is also used for my website, which should be semantically correct because my website is also about me, both the readme, repository, and website are all linked in topics. no file extension needed as per github files.

# Changelog
Self explanatory, attempts will be made to document changes in here.

# Docs
Self explanatory, attempts at explaining the repository will be here (you are also here btw). Please note I will try not documenting known html/css documentation, but instead, how my implementations of it work together. If you are looking for specific html/css documentation this is not the place.

# /SRC
The source folder for the website portion of this repository, as the other files are moreso housekeeping and not websitespecific. this folder and subsequent files and folders are scoped to the website only.

## Cloudflare
cloudflare is attatched to this repository, specifically, the /src folder. It checks if /src was updated, and if so, automatically rebuilds and deploys the updated version. Generally the rest of the repository is unused by cloudflare. Canonical link for this integration is `https://khaylapuppy.ca`

# Style.css
Style sheet for the entire site. style specific documentation can be found as comments inside this file. Its referenced by all html pages of my site, so it is a global style sheet for everthing.

# Pages
all pages are pretty similar, they share the same base layout and <head> elements, just their main content and structure beyond this varies between them

## Index.html
The entrypoint to my website. this file is the first page, and is the default unless a more specific address is used. It holds general information, warnings, user settings, and site specific documentation without any age gates.

## Profile.html
The profile page of my website. this file is for my primary page, eveyrthing of my profile is on display here. as some of it is suggestive and can cover some more mature and explicit themes, an age gate is present on this page to warn the user.

## Layout
The layout starts semantic, a <body> element, with 4 sub elements; <header>, <main>, <nav>, and <footer>.

The header has the page title and its own nav for changing between pages on my site, its the primary nav for this reason. the main element holds all page specific content, its the primary element of the page and the whole purpose of the page to begin with. the secondary <nav> element after the main content is a webwring nav, used for navigating between webrings. and finally <footer> closes the page with a nice copy-paste end note

aside from the secondary webring nav, this layout is a very semantic and standard layout. that doesnt mean its boring though! because the content within <main> is abolsutly up for styling. the webring nav can really be placed anywhere, but it depends on the webrings you are apart of, and generally it should be placed somewhere accesible without much hassle to allow users to continue the ring. placements can depend on the webring you are apart of also, but the bottom of a page is a pretty standard acceptable place for one so I placed mine here.
