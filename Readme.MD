# Fizz Buzz Test Driven Development


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Methods](#methods)
  - [factorial](#factorial)
  - [reverse](#reverse)
  - [fizzbuzz](#fizzbuzz)
- [Running Tests](#running-tests)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use the Fizz Buzz class in your Ruby project, you need to include the `fizz_buzz.rb` file in your codebase.

1. Clone the repository or download the `fizz_buzz.rb` and `tests.rb` files.
2. Copy the `fizz_buzz.rb` and `tests.rb` files into your project directory.

## Usage

After including the `fizz_buzz.rb` file in your project, you can create an instance of the FizzBuzz class and call its methods as needed. Here's an example:

```ruby
# Create an instance of the FizzBuzz class
fizz_buzz = FizzBuzz.new

# Calculate the factorial of a number
factorial_result = fizz_buzz.factorial(5) # Returns 120

# Reverse a string
reversed_word = fizz_buzz.reverse("hello") # Returns "olleh"

# Play the FizzBuzz game
fizzbuzz_result = fizz_buzz.fizzbuzz(15) # Returns "fizzbuzz"
```

## Methods

### factorial

The `factorial` method calculates the factorial of a given number.

#### Parameters

- `number` (Integer): The number for which the factorial needs to be calculated.

#### Returns

- The factorial of the given number.

#### Example

```ruby
fizz_buzz = FizzBuzz.new
factorial_result = fizz_buzz.factorial(5) # Returns 120
```

### reverse

The `reverse` method reverses a given string.

#### Parameters

- `word` (String): The word to be reversed.

#### Returns

- The reversed version of the given word.

#### Example

```ruby
fizz_buzz = FizzBuzz.new
reversed_word = fizz_buzz.reverse("hello") # Returns "olleh"
```

### fizzbuzz

The `fizzbuzz` method applies the FizzBuzz game logic to a given number.

#### Parameters

- `number` (Integer): The number to be processed.

#### Returns

- A string based on the FizzBuzz rules:
  - If the number is divisible by 3, returns "fizz".
  - If the number is divisible by 5, returns "buzz".
  - If the number is divisible by both 3 and 5, returns "fizzbuzz".
  - For any other case, returns the number as a string.

#### Example

```ruby
fizz_buzz = FizzBuzz.new
fizzbuzz_result = fizz_buzz.fizzbuzz(15) # Returns "fizzbuzz"
```

## Running Tests

To run the tests for the Fizz Buzz class, make sure you have the `rspec` gem installed. If you don't have it installed, you can install it by running:

```
gem install rspec
```

Once `rspec` is installed, navigate to the project directory and run the following command:

```
rspec tests.rb
```

This will execute the test suite

 and show the results.

## Contributing

Contributions to the Fizz Buzz project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

When contributing, please ensure that you follow the existing coding style, write comprehensive tests, and provide a clear description of the changes made.

## 👥 Authors <a name="author"></a>

- Alejandro Velasquez: [Github](https://github.com/VelzckC0D3) | [Linkedin](https://www.linkedin.com/in/velzckcode/)
- Daniel Falcon: [Danfall369](https://github.com/Danfall369) | [Linkedin](https://www.linkedin.com/in/danfall/) | 

## License

The Fizz Buzz project is open-source and available under the [MIT License](LICENSE).