# friendly

To run:
`clojure -m rebel-readline.main`

Then type

```clojure
(require '[clojure.spec.alpha :as s])
(require '[expound.alpha :as expound])
(set! s/*explain-out* expound/printer)

(require '[pyro.printer :as printer])
(printer/swap-stacktrace-engine!)
```

Thanks to @bhauman, @bhb, and @venantius

Oh, and there's this:
https://gist.github.com/bhb/2686b023d074ac052dbc21f12f324f18
