# url-redirect
Redirect to webpages using https://yourdomain.com/go.html?url={your_url_here}

# Instructions:
1. Donwnload the "sample.htaccess" file and the "go.html" file.
2. Customize the "go.html" file to match your layout for your site (Note: Do not remove the content in the script tags, that's what makes the whole thing run)
3. Change the "sample.htaccess" file to match the filename of your "go.html" file (RewriteRule ^test[^/]$ test.html <-- edit the filename and extension)
4. Upload your files to your website like mine (imcanada.eu / imcanada.cf).
5. Finally rename the "sample.htaccess" file to just ".htaccess" (unless you already have one of course)

# Testing
Test this script to see if you like it by going to https://imcanada.cf/go?url=https://google.com/. Just like magic you will be sent onto google.com via my site first.

# Customization
Of course you can change the script to your needs, for example I set up a simple "adf.ly-like" system by adding a timer and a progress bar which you can see here: https://zreddx.net/go?url=https://google.com/

# If you don't trust my links then don't use them
