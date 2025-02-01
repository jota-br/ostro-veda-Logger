# Logger Class

The `Logger` class in the `ostro.veda` package provides functionality for logging exceptions to a file. It includes methods to format the stack trace of an exception and write it to a log file.

## Features

- Logs exceptions to a file with a timestamp.
- Formats stack trace information for easy readability.
- Writes log entries to a daily log file.

## Usage

To use the `Logger` class, simply call the `log` method with an exception as its parameter.

### Example

```java
try {
    // Code that might throw an exception
} catch (Exception e) {
    Logger.log(e);
}
