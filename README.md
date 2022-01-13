# Scientific-Calculator

# Graphical user interface specification

1. Input and Output fields – the application should provide the option to input the numeric values from
keyboard. It should also correctly display at least the result of the last computation, more conveniently,
it can display a list of last results, or even the expressions along with their results.

2. C, CE and DEL buttons – allow to delete the current input, erase the memory and delete the last
digit/operator from the user input respectively.

3. Equals sign button – starts the computation.

4. Number buttons, Decimal mark button – allow to input numeric values without using keyboard, include
hexadecimal values as well.

5. Basic maths operation buttons – include addition, multiplication, subtraction, division and modulo
operations, other operations are optional.

6. Numeric base option – allows the user to choose in which numeric base the numbers are represented.
The number buttons should be enabled / disabled accordingly to the current base selected (e.g. with
binary numbers, only 1 and 2 are enabled).

7. Advanced maths operation buttons – include sinus, cosinus, exponential function and logarithm with
the base of 2. User can choose whether the advanced operations are displayed or hidden.

# Functionality specification

• The calculator has memory storing the result of the last computation.
• The next computation can use the value in memory as its first operand.
• User is able to provide input expressions from the keyboard. Its up to you whether you allow only numbers
and simple operators or enable other functions (sinus, etc.). The application should check the format and
ensure the correctness of the user input. A warning should be shown in case of incorrect input.
