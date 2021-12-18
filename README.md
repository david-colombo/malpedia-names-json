# malpedia-names-json

Since Malpedia (https://malpedia.caad.fkie.fraunhofer.de/) doesn't release a file containing all the known malware names with associated malware printables and aliases I decided to manually scrape the data and make the public here as json file.

An entry might look like this:

```
{
  "malware": "win.404keylogger",
  "malware_printable": "404 Keylogger",
  "aliases": [
    "404KeyLogger",
    "Snake Keylogger"
  ]
}
```

Last updated: 17. December 2021
