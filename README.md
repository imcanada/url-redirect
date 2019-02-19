# url-redirect
Redirect to webpages using https://yourdomain.com/go.html?url={your_url_here}

Make sure that the url after "?url=" is written with proper protocols included, for example: for sites with SSL use "https://{domain}.com" for ones without ssl simply type "http://" instead of "https://"

# Instructions:
1. Donwnload the ".htaccess" file and the "go.html" file.
2. Customize the "go.html" file to match your layout for your site (Note: Do not remove the content in the script tags, that's what makes the whole thing run)
3. Change the ".htaccess" file to match the filename of your "go.html" file (RewriteRule ^([^\.]+)$ "go.html" <-- Edit this on this line "RewriteRule ^([^\.]+)$ go.html [NC,L]")
4. Upload your files to your website like mine (imcanada.eu / imcanada.cf).
5. If you already have a .htaccess just copy the code from our one.

# Testing
Test this script to see if you like it by going to https://imcanada.cf/go?url=https://google.com/. Just like magic you will be sent onto google.com via my site first.

# Customization
Of course you can change the script to your needs, for example I set up a simple "adf.ly-like" system by adding a timer and a progress bar which you can see here: https://zreddx.net/go?url=https://google.com/

# Support
Post problems in issues, I don't know if i'll ever look at it but it's worth the try. My advice is "If you screw it up, start all over again".

# If you don't trust my links then don't use them
