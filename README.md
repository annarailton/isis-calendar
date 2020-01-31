# isis-calendar

A _very_ simple Hugo-powered site that keeps all the info about what's happening on the Thames. 

To get something added or for corrections to the content please open a PR or email frcc.harbourmaster@gmail.com

## Location of data

Data is all under the [`content`](https://github.com/annarailton/isis-calendar/tree/master/content) directory, in appropriately named `.md` files ([link to markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)). Nothing else _should_ need changing unless you want to play with how the site looks. 

## Running locally

You'll need both `golang` and `Hugo` installed:

* [Install `go`](https://golang.org/)
* [Install `Hugo`](https://gohugo.io/)

Check that it all works by doing 
```bash
hugo version
```

Clone this repo, navigate to the top of the folder and do
```bash
hugo server -D
```
You can then see the site on `localhost` - the prompt will tell you which port. 

## Other

Hugo theme is [https://github.com/panr/hugo-theme-terminal](https://github.com/panr/hugo-theme-terminal)