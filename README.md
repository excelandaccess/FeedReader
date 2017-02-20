#README.md

#FeedReader Project

####Version 1.0

[view in github](https://github.com/excelandaccess/FeedReader.git)

Description: Use Jasmine to generate test scripts for RSS feeds.


### Instructions:

1. Open index file in root using Google Chrome Web Browser.
2. Scroll down to bottom to see the test completed and the results by the jasmine tests from `jasmine/spec/feedreader.js` 

### Tests:

#### RSS Feeds:
__Feeds are defined and not empty__ - make sure that the allFeeds variable has been defined and that it is not empty. 

__Each feed has a URL defined and URL not empty__ - loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty

__Each feed has a NAME defined and NAME not empty__ - loops through each feed in the allFeeds object and ensures it has a NAME defined and that the URL is not empty

#### The Menu:
__Menu is hidden by default__ - Menu element starts off hidden

__visibility changes when clicked__ - the menu changes visibility between hidden and visible when the menu icon is clicked


#### Initial Entries:
__at least 1 item__ - there is at least a single .entry element when feed complete initial load

#### New Feed Selection:
__New feed changes__ - when a new feed is loaded by the loadFeed function that the content actually changes
