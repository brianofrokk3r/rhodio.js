# rhodio.js

*Rhodio* is a simple HTTP benchmarking tool.

### Help
```
node rhodio --help
```

### Options
```
-h, --help             output usage information
-V, --version          output the version number
-t, --time <n>         Total time to elapse (seconds)
-c, --concurrency <n>  Number of concurrent requests (requests/second)
-x, --post <s>         Post parameters in quoted querystring form ( e.g. "foo=1&baz=2" )
-h, --host <s>         HTTP host to request in quotes
```

### Example
##### Input
```
node rhodio -t 5 -c 1 -x "foo=1&baz=2" -h "http://www.rokk3rlabs.com"
```
##### Output
```
Elapsed Time: 5 seconds
Concurrency: 1 request/second
```

### To-Dos
* Error Handling
* Unit Tests