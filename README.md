# friendly
```clojure

(require '[expound.alpha :as expound])
(set! s/*explain-out* expound/printer)

(require '[pyro.printer :as printer])
(printer/swap-stacktrace-engine!)
```
