Note from _codecademy.com_, structured by codes followed with explanations.

## Part 1

### 1 Name

	"MyNameIsPig"
	
	"MyNameIsPig".length

1.1 The second line gains how many characters the string contains.
1.2 The `length` cannot be applied to numbers. For instance,

	2.length
	
returns an error.


### 2 Interactive

#### 2.1 Confirm

	confirm('bonjour')
	
2.11 Runing this will popup an interactive block, like a message.

2.12 If it is confirmed, by clicking the "OK" of the block, a true value is returned.


#### 2.2 Prompt

	prompt('Ca va?')
	
2.21 Runing this will popup an interactive block, like a message.

2.22 It returns a string with content being what you have typed in the block.

### 3 Data Type

1. Number: `2`
1. String: `"hello"`
1. Boolean: `true` and `false`

#### 3.1 Boolean

	"what's wrong".length > 10

3.11 `>=` for no less; `<=` for no more. `===` for if-equal; `!==` for if-non-equal.

### 4 Print

	console.log(2*5)
	console.log("Hello")

console.log() will take whatever is inside the parentheses and _log_ it to the _console_ below your code -- that's why it's called console.log()!


### 5 Condition

	if (1 !== 2) {
		console.log("then 2 != 3."); }

or

	if (1 === 2 ) {
		console.log("Let's go down the first road!"); }
	else {
		// What should we do if the condition is false? Fill in here:
		console.log("2 = 3.") }

#### 5.1 Syntax for `if` is

	if (condition) {
		statement_1;
		statement_2;
		...... }

or for `if / else` is

		if (condition) {
			statement_1;
			...... }
		else {
			statement_i;
			...... }


### 6 Substring

	// Be careful with the substring's letter positions!
	"wonderful day".substring(3,7)

which retrns
	
	"derf"

6.1 `substring(x, y)` returns the characters between positions `x` and `y`.

6.2 *Position begins at zero!*
