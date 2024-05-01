# Amazing Numbers

This is a Java project that allows users to explore interesting properties of numbers. The project is built with Gradle and can be run in any IDE that supports Java, such as IntelliJ IDEA.

## Features

- **Number Properties**: The application can determine various properties of a number such as whether it's even, buzz, duck, palindrome, gapful, spy, square, or sunny.

- **Range of Numbers**: The application can process a range of numbers and display their properties.

- **Property Search**: The application allows users to search for numbers with specific properties.

## How to Run

1. Clone the repository to your local machine.
2. Open the project in your preferred IDE (IntelliJ IDEA recommended).
3. Run the `Main.java` file located in the `numbers` package.

## Usage

Upon running the application, you will be greeted with a welcome message and instructions on how to use the application. You can enter a single number to know its properties, or two numbers to obtain the properties of a list of numbers. You can also specify properties to search for.

## Code Structure

- `Main.java`: This is the entry point of the application. It creates an instance of the `UI` class and runs the user interface.

- `UI.java`: This class handles all user interactions. It prints the welcome message, gets user input, and processes the input according to the user's request.

- `Numbers.java`: This class contains methods for determining the properties of a number. Each method takes a number as input and returns a boolean indicating whether the number has the property.

## Contributing

Contributions are welcome. Please open an issue to discuss your ideas before making changes.

## License

This project is licensed under the MIT License.
