# Complexity
# Before refactoring 
* Very repetitive use of if else  
* Check values and presence of input selected in prompt
* Using an `else{}` after `if{}` while there is nothing more to execute after


# After refactoring 
 * Using  `switch case` to avoid repetitive `if/else` 
 *  No more verification of the choosen input value 
 * Added a default in `switch` , so that if there is no value it will return 'invalid choice'.
* No more `else` in a condition but the value directly returned after the if or else if
