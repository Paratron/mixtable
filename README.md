# mixtable ♻

Mixtable is a debugging/development tool for web requests (HTTP, Websocket)

## Motivation

In the past, I was using tools like [Fiddler](https://www.telerik.com/fiddler) a lot. Since the devtools in firefox and chrome gotten better through
the years, I found myself using a debugging proxy only rarely.

However, during the development of my current project, I often have the need for simulating API call failures, missing
data, invalid data and such. I wanted to have a simple tool where I can monitor what API requests are being made and the
possibility to say: the next request of this kind should fail. Or apply functions that modify the returned data on the fly.

I know this is possible with Fiddler and the likes, but found it to be very tiresome to set up.

And in the end, I was unable to find a tool where I can do the same for websocket connections, so I want to try my own approach.



