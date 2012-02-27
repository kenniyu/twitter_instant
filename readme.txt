I decided to turn this little project into a web app with just one page.  I wasn't sure when to query the search (user presses a search button?) so I made it like Google's instant-search :) 

The relevant view file is index.ejs
The relevant stylesheet is public.css
All javascript files are in public/javascripts
Stylesheets and javascript files are included in the head of index.ejs

Since some queries may return many results, they're paginated like how Tumblr or Facebook does their lazy-loading.  Scroll down to the bottom and it'll automatically load the next batch of results.

You can also filter by a few options:
English
+
Popular, Recent, or All (mix of popular and recent) tweets


Thanks and happy instant-tweet-searching!