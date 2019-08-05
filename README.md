# go-sickchill-api

📺 A simple wrapper for the [SickChill](https://github.com/SickChill/SickChill) API written in Go, created mainly for its role in [ChillBot](https://github.com/noam09/chillbot), a [Telegram](https://telegram.org) bot for SickChill. 

## Usage

```go
// Initialize SC client
sc := sickchill.NewClient(hostname, port, apiKey, urlBase, ssl)
// Get search results
res, err := sr.SearchTVDB("recreation")
```

## TODO

* Quality selection
* Check if show exists in library

## License

This is free software under the GPL v3 open source license. Feel free to do with it what you wish, but any modification must be open sourced. A copy of the license is included.
