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
