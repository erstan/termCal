# termCal
A failed attempt at designing an expression parser!


Demo at <https://erstan.github.io/termCal>
## Guide
  * Basic mathematical operators, `+`, `-`, `*`, `/`, `%`, `^` supported for integers and floating point numbers
  * `clear` erases the results form previous commands
  * `history` gives the previously evaluated expressions and their results
  * `dark`/`light` can be used to switch the console theme
  * `#` can be used to disable command tracking
  * Pressing <kbd>Enter</kbd> without a command string gives the result of the last succesfully executed operation
## Todo
Although the frontend is beautiful, the underlying parser and the evaluator function is not that strong! It can only support a few basic mathematical operations for now. It needs to rewritten to support variables, functions, and perhaps <s>control statements like if-else and for loops</s>.
