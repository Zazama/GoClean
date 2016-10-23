# GoClean
Clean and Responsive Ghost Theme

It supports the latest updates and has the navigation helper implemented.
New version makes use of the get helper to display latest posts on all pages.
Enable it in your Labs settings to display latest posts in the right sidebar.

You can find a demo here: http://www.zazama.de/

# How to use Disqus
Go to the partials folder and edit the disqus_name.hbs file. Remove the content and enter your Disqus shortname

NOTE: IF THIS DOESN'T WORK, EDIT THE POST.HBS, DELETE THE {{> "disqus_name"}} AND INSTEAD ENTER YOUR SHORTNAME HERE!

# Latest changes
- v1.0.2: Changed bg, use get helper to display latest posts, reindent
- v1.0.1: Added 'next_post' and 'prev_post' helper