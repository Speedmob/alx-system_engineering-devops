0-alias: create an alias called ls for rm *

1-hello_you: prints 'hello user', where user is the user's name by using $USER variable

2-path: adds :/action to $PATH output

3-paths: counts the number of directories in the PATH by counting the number of : in between (translated : to \n then counted using grep -c \n)

4-global_variables: printed using env, which prints enviromental variables by default if no parameters are entered

5-local_variables: prints all variables (local and enviromental) using set

6-create_local_variable: creates a local variable called BEST with value School

7-create_global_variable: creates a global variable called BEST with value School using export

8-true_knowledge: adds 128 to the value of TRUEKNOWLEDGE and prints it using echo

9-divide_and_rule: Divides POWER by DIVIDE and prints the results using echo

10-love_exponent_breath: prints BREATH to the power of LOVE using **

11-binary_to_decimal: converts binary to decimal using # (built-in)

12-combinations: prints all possible combinations of two letters, except oo by first getting all possible combinations, then translating the spaces between them to new lines and printing anything other than oo using "grep -v"

13-print_float: prints a float number with 2 decimals then a new line using printf "%.2f\n" (var name)

100-decimal_to_hexadecimal: turns decimal to hexadecimal using printf "%x\n"

101-rot13: encrypts the message by translating the letters to different letters by a specific pattern
