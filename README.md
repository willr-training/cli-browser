# cli-browser

## MacOS terminal

### Chrome

https://superuser.com/a/1383357/1112071

Open a URL in the default browser (could be Chrome):

`open http://www.example.com`

Open a URL in Chrome always (using the app name):

`open -a "Google Chrome" http://www.example.com`

Open a URL in Chrome always (using the app path alternative syntax):

`open -a /Applications/Google\ Chrome.app/ http://example.com`

Open a URL in Chrome always (using the bundle identifier alternative syntax):

`open -b com.google.chrome http://www.example.com`

Open a URL in Chrome in an incognito window always:

From man open, it would seem that you should be able to do it like this (but alas it does not seem to get the incognito option to Chrome):

`open -a "Google Chrome" http://example.com/ --args --incognito`

However, you can do it by passing the Chrome [command line switches](https://peter.sh/experiments/chromium-command-line-switches/) directly to the Chrome binary:

`/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --incognito http://example.com`

### Brave

## Windows 

### Brave

Open url in Brave<br>
`start brave example.com`

Open url in Brave incognito<br>
`start brave google.com --incognito`

### Chrome

Open url in Chrome<br>
`$ chrome google.com`

Open url in Chrome incognito<br>
`$ chrome google.com --incognito`

## Other tools to look into

Google search from terminal<br>
https://www.tecmint.com/google-commandline-search-terminal/
https://github.com/jarun/googler




