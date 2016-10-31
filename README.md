<span style=display:none; >[You are now in GitHub source code view. Click here to view README file in GitHub Pages view]
( https://jaanga.github.io/gubgub/#README.md "View file as a web page." ) </span>
<input type=button onclick=window.location.href='https://github.com/jaanga/gubgub/';
value='You are now in a GitHub Pages view. Click here to view README file in GitHub source code view.' >

[Jaanga]( https://jaanga.github.io ) &raquo;

[GubGub Read Me]( https://jaanga.github.io/gubgub/index.html#README.md )
================================================================================

_<small>
    Explore and monitor the <a href="https://github.com/about" target="_blank" >many GitHub projects</a>
    helped by the <a href="https://developer.github.com/v3/" target="_blank" >GitHub API</a> and client-side cookbook JavaScript.
</small>_

<img src="https://jaanga.github.io/gubgub/gubgub-r1.jpg" style=display:none; width=800 >

<span style=display:none; >Full screen: [Jaanga GubGub]( https://jaanga.github.io/gubgub/ )</span>
--------------------------------------------------------------------------------

<!--
<iframe id=ifr src=https://jaanga.github.io/gubgub/gubgub-r1.html width=100% height=600px ></iframe>

_Jaanga GubGub R1_

***
-->

<div id=READMEbespokeText ></div>

Concept
--------------------------------------------------------------------------------

GitHub has [millions of projects]( https://github.com/about ).

With so many projects, finding GitHub projects that may be of interest to you is not easy.

Finding projects with code you might actually want to fork use is even less easy.

And then, when you identify a GitHub user of interest, it's not that easy to explore the user's work.

When you find somebody you like, it's not easy to:

* Monitor what they have done recently
* Search the many repositories
* Discard material that looks interesting - but has not been updated in years

Then there's the other side of the coin:

* How can you make your own work more visible to the world?
* How can visitors to your GitHub projects become informed in a speedy, fun manner about all the things you are doing.

Certainly the [Explore GitHub]( https://github.com/explore ) page is a good place to start.

And there are a number of really interesting curation efforts. See 'Links of Interest' below.

And none of that stops you or us from investigating even more ways of exploring GitHub.

And, guess what, GitHub supplies a quite amazing tool for finding stuff on GitHub.

The [GitHub Developer API]( https://developer.github.com/ ) provides fast, free and easy access to millions of GitHub projects.

So, if you are looking to build tools to:

* help you snoop around GitHub
* find the things that are of particular interest to you
* and monitor their progress

then you have come to a good place...


### Mission

* Help you build tools that make the GitHub web pages and the data come to you
	* Reduce that endless click to go there and click to come back, click go there and click come back - repeated endlessly
    * 'You don't have to go there. It comes to you.' - Henrik Bennetsen
* Provide you with as many ways as possible for viewing content and statistics - really quickly and easily readable
* Display ways of getting to content such as the README files and gists wherever possible
	* Show what is being created in a timely fashion
* Create a variety of versions - from very simple to totally custom-tailored for a particular user
* Replicate in various languages and dialects


### Vision

* Help you discover new algorithms and new concepts
* Link associated projects that you had no idea they were associated
* Transfer all of this into your own set of tools


Usage / Features
--------------------------------------------------------------------------------

The client-side JavaScript script creates and updates three columns of data/content


### Left Column / Menu / Buttons and Links

#### Things you can do as a user

* Click on title to reload
* Direct link to this read me file
* Select or enter your own search query
* Select or enter a GitHub user name < try your name ;-)
* Note the updates to the User Data section
* Click every button in GitHub User Data
* Buttons are in three columns
    * Left column buttons: cause unformatted search results to display in center columns
    * Middle column button: cause search results to display in a table
    * Right column links: open new tab to related GitHub web page or Google search results
* Note the many different ways of exploring the same search results

#### Things you can do as a coder

* Note usage of new HTML 5 `<details>` tag in the menus
* Edit 'usr-users.js' and add your user name and search queries that interest you
* Consider other ways of displaying the data returned by the GitHub Developer API
* Consider ways of improving the UI
* Simplify the menu so it just handles your particular needs


### Center Column / Contents / Tabular Data / Reports

* Displays scrolling list of the various search results
    * Initiated by button-clicks in the left column
* Displays README file - and any file in Markdown format
* Adds iframe views of README files for repositories

#### Things you can do as a user

* Click the numerous links throughout
* Consider ways in which the user experience could be improved

#### Things you can do as a coder

* Consider adding more links to the search statistics report under each iframe
* Consider adding iframes to view data other than the repos


### Right Column / Updates / Activity

* Mission: Show you - and link to - what the user or organization has accomplished recently
* Loads and display users 100 most recent events sorted by date
* Most aspects of each event are links to most appropriate GitHub page

#### Things you can do as a user

* Scroll up and down. Click on items of interest
* Identify and report incorrect or better URLs for each type of event

#### Things you can do as a coder

* Consider ways of displaying other types of search results or data in this column



Coding Style
--------------------------------------------------------------------------------

### Mission

* We live in a world where the [full-stack developer]( https://www.sitepoint.com/full-stack-developer/ ) reigns supreme
* We champion [DevOps]( https://en.wikipedia.org/wiki/DevOps ) as if good DevOps is the primary goal

But:

* What if you are an entry-level coder?
* What if you are interested in STEM topics than [DevO.ps]( http://devo.ps )?

Then you have come to the right place.


### Written for GitHub Users and Coders

You are here to explore code, therefore:

* Font is default monotype font - fixed character spacing
* UI is minimal
	* Offers many - too many? - options
* Uses most up-to-date JavaScript features
* Displays the identical data using varying methods

But some idiosyncrasies:

* Follows [Mr.doob coding style]( https://github.com/mrdoob/three.js/wiki/Mr.doob's-Code-Style%E2%84%A2 )
	* Open airy, almost a poetic style of displaying code
* Does not follow normal split up of HTML, CSS and JavaScript
	* Content, appearance and behavior
* Does follow the idea that its all mutable stuff in the DOM
	* Even content
	* It all starts as alphanumeric characters and ends up as pixels
	* Remix, re-appropriate, re-hash as needed
	* Uses JavaScript to do this mash-up
    * It's <s>[turtles](https://en.wikipedia.org/wiki/Turtles_all_the_way_down )</s> JavaScript all the way down

There are hundreds of computer programming languages.
And so, there can be many styles of coding in each language. And each can have its own beauty.


### Entry Level Code / Cookbook Style

* Code is almost all entry level JavaScript
* Download and run
* JavaScript is used for everything including
	* Adding HTML
	* Applying CSS
* The dependencies are:
	* ShowDown Markdown interpreter
	* GitHub API

### Compatibility

* Anticipated user: somebody who writes code
	* Sitting in front of a modern computer with recent multi-core CPU and Intel HD4000 GPU
	* Display 1600 x 900 pixels or better
* Every effort made to use latest most simple methods
* Tested on latest Chrome, FireFox, Edge and Safari
* Tested on Windows and MacOS
* Operation on Android and iOS is a bonus not a requirement
* Backwards compatibility eschewed
	* Adds complexities to scripts
	* Strikes fear in the hearts of new users
	* Looks to the future not the past
	* Simple features in the pipeline are built on the lessons learned from the complextiies of the past  


### No Server Needed

* 100% client side
* Loads scripts from GitHub pages or localhost
* Uses Rawgit as a content delivery network (CDN)
* Accesses GitHub Developer API via [RESTful]( https://en.wikipedia.org/wiki/Representational_state_transfer ) URL calls
	* No terminal window/ [curl]( https://curl.haxx.se/ ) needed here

### Namespace, Variable Names and File Namespace

    * Menu and column headers have tooltips that indicate namespace and script name.
    * Example: the Select menu has `SEL` as a namespace and `sel-select-r1.js` as a file
    * Every script is in its own folder with its own HTML testing file


Scripts
-------------------------------------------------------------------------------

* The app is built using a number of script files
* Each item on the menu has its own script file
* Each script file has its own folder
* Each script file has its own HTML file to help with testing and developing the script
* Each script file has its own three letter namespace object
	* See [JavaScript Object Management]( https://developer.mozilla.org/en-US/Add-ons/Overlay_Extensions/XUL_School/JavaScript_Object_Management )
* The namespace title relates to the title of the menu
* The three letter namespace is part of the script folder and file title

_The following describes the usage of each script_

### [COR / 0-cor-core-r1.js ]( https://github.com/jaanga/gubgub/tree/gh-pages/0-cor-core )

COR.converter = new showdown.Converter( { strikethrough: true, literalMidWordUnderscores: true, simplifiedAutoLink: true, tables: true });

* Set up the HTML for the three columns: menu, contents and updates
	* Builds header and footers
* Adds style sheet data
* Include AJAX and location.hash onchange event handling utilities used by the other scripts

### [API / api-authentication-r1.js ]( https://github.com/jaanga/gubgub/tree/gh-pages/1-api-authentication )

API Call: [https://api.github.com/rate_limit]( https://api.github.com/rate_limit )

* Enable you to enter your GitHub Developer API access token
    * Use location.hash in form of: '#token=#your_token#' then reload the page or click 'Set API Access Token'
    * Or paste access token into text input
* Provides a readout of:
    * GitHub API Usage limits
    * Number of uses remaining
    * Time when clock will return to zero


### [SEL / sel-select-r1.js ]( https://github.com/jaanga/gubgub/tree/gh-pages/2-sel-select )

API calls:
* [https://api.github.com/search/repositories?q=stars:>60000]( https://api.github.com/search/repositories?q=stars:>60000 )
* See [GitHub Developer API Search]( https://developer.github.com/v3/search/ )

#### Select Type of GitHub User
* Select a pre-written search query
* Edit or enter your own query

Most of your interaction will occur here

### Select GitHub user and repo

* Select a user from the list of results
* Enter a user name of your choice


### [DAT/ dat-data-r1.js ]( https://github.com/jaanga/gubgub/tree/gh-pages/dat-data )

API Calls:
* [https://api.github.com/users/mrdoob]( https://api.github.com/users/mrdoob )
* Click every button and every link and see what happens
* Display the data for every item in the search results
	* Left column of buttons: display raw data
	* Displays prettified data
	* Links to appropriate GitHub page for the data


### [EUS / eus-events-user-r1.js / user-events-big-r1.js ]( https://github.com/jaanga/gubgub/tree/gh-pages/eus-events-user )

* Three ways of viewing user/organization events
    * As a tight vertical list ~ see right column: COR.updates
    * By repository and type ~ See COR.center ~ default when you load a new user
    * By date with details ~ see COR.center ~ click 'events' button in left menu or 'show events by date in detail' button in right menu

### [USR/ users-r1.js ]( https://github.com/jaanga/gubgub/tree/gh-pages/usr-users )

* Default data used by SEL
* Items used to create options for SELselGroup
* Items used to create options for SELselUser
* Could be more accessible if in SEL?
* Could be created by via a Gist?
* Very much part of any effort to create bespoke GubGubs



Editing the Code
--------------------------------------------------------------------------------

<iframe src='https://jaanga.github.io/cookbook-html/examples/libraries/ace-editor/ace-view-r1.html#
	https://jaanga.github.io/cookbook-html/templates/github-api-user-explorer2/github-api-user-explorer2-r1.html' width=100% height=600 ></iframe>

<input type=button onclick=window.location.href='https://github.com/jaanga/jaanga.github.io/blob/master/cookbook-html/templates/github-api-user-explorer2/github-api-user-explorer2-r1.html';
value='Source code listing' >


* Open this file: https://github.com/jaanga/jaanga.github.io/blob/master/cookbook-html/templates/github-api-user-explorer2/github-api-user-explorer2-r1.html
* Click the 'Raw' icon and save the raw file to your computer
* Once you've downloaded the file, you can click it to run it.
* Open the file with a text editor


Naming this App
--------------------------------------------------------------------------------

New name: GubGub

The code or original name for this script was 'GitHub API User Explorer'.
This title describes fairly clearly what the script's intention but does not comply with the [GitHub Logos and Usage]( https://github.com/logos ) guideline.
Examples of app names that the GitHub organization accept are listed on the GitHub [Integrations]( https://github.com/integrations ) page.
The only of integrations with the word 'github' in the title are apps produced and distributed by GitHub themselves.

So we needed a more acceptable name.

* The title should relate to the intent
* The intent is to help people peruse GitHub
* The title should not infringe GitHub Trademarks
* Should be short and catchy
* Little relation to git more relationship with 'hub'

The current solution is 'gubgub' or 'ghubghub'.

The fun thing is that Gub-Gub is the talking pig in the Dr Dolittle series of books written by Hugh Lofting in the early 1900s

See

* https://en.wikipedia.org/wiki/Doctor_Dolittle
* https://en.wikipedia.org/wiki/Gub_Gub%27s_Book




Issues
--------------------------------------------------------------------------------

* 2016-10-30 ~ Open README with link: loads user and overwrites README
* 2016-10-30 ~ USR: failing on reloads. Need to add valaes with actual login
* 2016-10-29 ~ COR? Duplicates in title.document
* 2016-10-29 ~ Double loads at times
* 2016-10-29 ~ Why is there an error: 2-sel-select/sel-select-r1.html ?
* 2016-10-28 ~ Decide whether or not all folder names have numbers
* 2016-10-28 ~ Reports error when cannot open README ~ probably unfixable
* 2016-10-20 ~ Microsoft Edge: Contents readme iframes not displaying data - probably issue with '/' in id




To Do List / Goals
--------------------------------------------------------------------------------

* 2016-10-29 ~ Add meta descriptions to all HTML files
* 2016-10-29 ~ Followers/Following: add ?sort=updated&order=desc&per_page=100'; - DAT all needs a good clean-up
* 2016-10-29 ~ Split into multiple versions
    * Phone versions
    * Monitoring favorites version
    * GitHub explorer version
* 2016-10-28 ~ Decide if better to open links in same tab or new tab
* 2016-10-26 ~ Allow for translation
* 2016-10-26 ~ Display current user in document.title
* 2016-10-26 ~ Contents and Updates titles uppercase
* 2016-10-26 ~ Add links to stats on events by repository and type
* 2016-10-26 ~ Events by repo: Display if a repo is owned by a user or an org
* 2016-10-20 ~ Add ability to display readme files in full
* Add number of stars to each repo < would add to rate limit
* Add iframes to orgs
* Add iframes to gists


Links of Interest / Background Context
--------------------------------------------------------------------------------

### Posts

* https://github.com/jaanga/gubgub/issues/2
* https://www.reddit.com/r/github/comments/5a8vzt/jaanga_gubgub_r1_explore_and_monitor_many_github/?ref=share&ref_source=link
* https://twitter.com/ta/status/792871595001847808

### Web sites that help you explore GitHub

* https://resume.github.io/ ~ added 2016-10-19
* https://github.com/trending
* https://github.com/trending/javascript
* https://www.reddit.com/r/github/
* https://www.reddit.com/r/coolgithubprojects
* https://github.com/leereilly/games
* http://www.gitlogs.com/
* http://ghv.artzub.com/
* http://github-awards.com/
* https://github-ranking.com/
* https://gist.github.com/paulmillr/2657075/
* http://githut.info/


### Credits

* [GitHub Developer API]( https://developer.github.com/v3/ )
* [Showdown]( https://github.com/showdownjs/showdown )
    * Showdown is a JavaScript Markdown to HTML converter, based on the original works by John Gruber.
    * Showdown can be used client side (in the browser) or server side (with NodeJs).


### README Considerations

* http://tom.preston-werner.com/2010/08/23/readme-driven-development.html
* https://github.com/noffle/art-of-readme
    * This README is much influenced by noffle's README


### Coding

* [Mozilla Developer Network (MDN) JavaScript]( https://developer.mozilla.org/en-US/docs/Web/JavaScript )
* [W3schools.com]( http://www.w3schools.com/js/ )
	* Much maligned by full-stack developers,
	* but it the first thing that show up on Google


### Coding Style

* [Mr.doob coding style]( https://github.com/mrdoob/three.js/wiki/Mr.doob's-Code-Style%E2%84%A2 )
* [Does Mr.doob approve your code style? ]( http://zz85.github.io/mrdoobapproves/ )
    * [MrDoob Approves – A Javascript CodeStyle Editor+Validator+Formatter Project]( http://www.lab4games.net/zz85/blog/2015/01/25/mrdoob-approves-a-javascript-codestyle-editor-validator-formatter-project/ )


### Users

* [theo-armour.github.io](  https://theo-armour.github.io )




Copyright and License
--------------------------------------------------------------------------------
Copyright © 2016 Jaanga authors. [MIT License]( #LICENSE.md )




Change Log
--------------------------------------------------------------------------------

### 2016-10-29

* Code clean-up
* Tested on briefly MacOS Sierra with Safari 10, FF49 and Chrome 54. All seem file
* Tested on El Capitan with Safari 9.1. Fail.
* Tested on iPad Pro with iOS 10. All seems fine.
* Tested on iPad Pro with iOS 9.3. Fail.
* Tested on Windows 10 with Microsoft Edge 14. Fail.
* Tested om Windows 10 with latest FF and Chrome. Seem fine.


### 2016-10-28

* Add to README
* Code clean-up
* 2016-10-26 ~ Type not updating with change in selection < fixes

### 2016-10-26

* Leaving and coming back returns to same user / better location.hash management
* Add GitHub no connection note
* Add API key entry
* Many additions to README
* More code clean-up
* Access token seems to ne working
* Ditto location hash
* 2016-10-21 ~ API ~ reset time not updating << fixed

### 2016-10-25 ~ GubGub R1

* New Jaanga repo


### 2016-10-23

* Much cleaning up all over the place

### 2016-10-20

* Major update to this README
	* Switch from read me to README ;-(
	* README is the standard


### 2016-10-19

* All buttons have working actions
* Buttons show hand icon on mouse over
* 2016-10-18 ~ Read all cases of readme.MD < mostly fulfilled


### 2016-09-20

* 2016-09-17 ~ return to top of page when new user is loaded < 2016-09-20 fixed
* Enter search query
* View rate limits
	* Add number of hits remaining before you go over usage limits
* Repo read me in monospace font
	* Add GitHub-like CSS < partial fix
* Right menu scrolls independently

### 2016-09-17 ~ Explorer2 R1

* Major update


### 2016-09-??

* First commit
* Add Read Me

***

<center title='Jaanga ~ your 3D happy place' >
# <a href=javascript:window.scrollTo(0,0); style=text-decoration:none; > ❦ </a>
</center>
