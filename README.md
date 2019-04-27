# idris-stlc
Verified typechecker and evaluator for Simply Typed Lamda Calculus (STLC) in Idris inspired by [this blogpost](https://plfa.github.io/Properties/). The evaluator are based on the progress and preservation theorems which are also proved. Run the example (on Windows) by loading the example module into the Idris REPL with  ```idris .\Example.idr -p pruviloj``` and evaluate and display the example with ```show (evalForget example)```.
