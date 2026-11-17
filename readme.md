# cf_youtube_patched

or known as custom filters for patched youtube (and yt music)

you don't like a specific element displayed? you can now make them disappear!

# the limitation

internally, youtube uses litho framework for the ui. see https://fblitho.com for more info about this framework

what this means is some elements cannot be hidden using custom filters alone. this is where direct complex ui editing in the code comes into play which is out of reach for us regular users

# creating a debug log

go to youtube / yt music → settings → morphe → miscellaneous → debugging and set the following:

* debug logging - debug
* litho logging - path and buffer

once done, restart the app. you can now start logging the `eml` elements by going to the desired page (home), make the element appear and disappear by scrolling far enough. you can then go back to the debugging section and press "export debug logs" (perform a search with `eml` or logical phrases like `certain_element`)

during this process, you may notice a slight lag (more noticeable on budget devices)
