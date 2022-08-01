usage
```
$ stringparse list --text "Hackers beware." --metric words --unique
textPtr: Hackers beware., metricPtr: words, uniquePtr: true
$ stringparse count --text "She sells sea shells by the sea shore" --metric substring --substringList se,sh,ea,he
textPtr: She sells sea shells by the sea shore, metricPtr: substring, substringPtr: , substringListPtr: [se sh ea he], uniquePtr: false
$ stringparse count --text "Komand Security"
textPtr: Komand Security, metricPtr: chars, substringPtr: , substringListPtr: [], uniquePtr: false
```

tutorial from https://www.rapid7.com/blog/post/2016/08/04/build-a-simple-cli-tool-with-golang/