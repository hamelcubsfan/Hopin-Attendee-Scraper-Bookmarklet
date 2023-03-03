# Hopin-Attendee-Scraper-Bookmarklet
Simple bookmarklet to scrape attendees from Hopin events.  

Save file as bookmark
Go to desired Hopin event which you have registered
Find "auth" in network activity 
Locate event ID and Bearer
Run the bookmarklet
When prompted, paste (or type) event ID
When prompted, paste (or type) Bearer (without the "Bearer", just the actually token)
Upon completion in the browser console, right click on arrow and "Copy Object"
Use your favorite JSON to CSV conversion tool (my fav = https://products.aspose.app/cells/conversion/json-to-csv)
All complete, you have a full CSV of attendees, names, bios, etc.  Enjoy

All credit to andrebradshaw for the JS.  I simply added prompts and a few lines for ease of shifting to a bookmarklet.
