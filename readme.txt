I decided to turn this little project into a web app with just one page.  I wasn't sure when to query the search (user presses a search button?) so I made it like Google's instant-search :) 

The relevant view file is index.ejs
The relevant stylesheet is public.css
All javascript files are in public/javascripts
Stylesheets and javascript files are included in the head of index.ejs

Since some queries may return many results, they're paginated like how Tumblr or Facebook does their lazy-loading.  Scroll down to the bottom and it'll automatically load the next batch of results.

One possible downside was trying to go back to the search bar at the top when a user scrolls too far down, so I've added a 'back-to-top' button that, when clicked, brings you back to the top of the page.

You can also filter by a few options:
English
+
Popular, Recent, or All (mix of popular and recent) tweets

To run the app locally you'll need node, express, and the ejs module, but that might be too troublesome, so you can just visit the app in the cloud at:
twitter_instant.nodejitsu.com

Also, all the source code is on github at:
https://github.com/kenniyu/twitter_instant

Thanks and happy instant-tweet-searching!