# DuckDuckGo_to_Google
It's annoying to open Google everytime DuckDuckGo dosn't find what we are looking for. This is the script to save time.
## How to?
Create a new bookmark in the Bookmarks bar of your favourite browser and insert as link:


`javascript:(function(){window.location.replace("https://www.google.com/search?q="+$("#search_form_input").val());})();`


Cheers
