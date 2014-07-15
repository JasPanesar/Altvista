Altvista
========

Result-focussed search presentation


##History & Status

Built in 2012.  Active at [Altvista.org](http://www.altvista.org)

##Context

Use of search engines since the 90's has consistently shown a shift from away from prominent presentation of search results for quick and easy consumption, to one optimized for a user to click on an ad instead of a search result.

Generally, search engines, while improving index quality, have [increasingly pushed an ad first approach to presenting results](http://www.businessinsider.com/google-has-taken-over-its-search-results-page-with-its-own-content-and-ads-2012-6), especially from 2008 to 2012.

![](http://i.imgur.com/mSO3Xp4.jpg)
[Image from above link](http://www.businessinsider.com/google-has-taken-over-its-search-results-page-with-its-own-content-and-ads-2012-6)

Enter in today's searches that you may do daily, or multple times a day, such as checking weather, bus or traffic information, etc, and you are faced with an increased cognitive load to arrive at the same result, especially if you do not make heavy use of bookmarking

## Original Idea

What if there was a tool focused on presenting search results for the user's productivity, instead of optimizing for clicks on ads?

From this came the initial version of a "search engine built in a morning".

I liked Altvista as a name because it literally is an alternate view of results, as well as a paying of respect to all tools which prioritized the visitor's time and needs of quickly locating relevant information, instead of having attention passed through ads first.

## Original Implementation

Finding the easiest and reasonable way to get search results and present them had a few interesting waypoints:

- Search engine API's, understandably, seem quite happy to make using their direct search the path of least resistance.
- Contextual search results, based on your personal search history and preferences, as well as location, etc, can often appear differently than API Search results.

- Despite API Search results that in some cases looked different than what the search engine itself presented, the preferred answer was overwhelmingly present in the first 10 results.
- For regularly performed searches, you generally do not need more than the first 5 or 10 results.

- Built initial proof of concept on a Saturday morning
- Tweaked basic features enough to make it functionally usable on a regular basis

##  Key Features

- Auto-Load: Extending the "I'm Feeling Lucky" type feature, the first search result is automatically loaded in an iframe.  This does not work on all sites that detect for iframes (Youtube, etc), but for informational type sites I have not had many issues.  A neat aspect of this feature is if you type in a more exact search (ie., weathernetwork edmonton) you effectively can use keywords to bring up a search result. Would like to improve this.  
- URL Based search possible -- I odn't use it a lot but a search can be directly entered via URL
- Open search compatible -  so browsers can add AltVista as a default search engine.  Alternatively in Chrome, you can type altvista.org, press Tab and the autocomplete will allow you to search directly and selectively via AltVista.org.
- Side bar of results - The first 5 or 6 search results are loaded on the right side of the display window.  Clicking on any result will load the result in the frame.


## Roadmap

My current goal is to use the search for a long period of time to notice the subtle aspects I seek in search results and then revisit a new version.  I have some ideas for the UI, including building more of the functionality into the top bar.


## License

At present:

http://creativecommons.org/licenses/by-nc-nd/4.0/

Copyright 2012 Jas Panesar
