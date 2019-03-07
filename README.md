# PHP Console
Manipulate the front end console with PHP.

## Hello World example
```
require_once "console.php";
Console::log("Hello, World!");
```
![Screenshot](Hello%2C%20World!.jpg)

## Documentation

### `void Console::clear()`
Clears the console.

### `void Console::count()`
Logs the number of times that `count()` has been called with a particular label.

### `void Console::count_reset()`
Resets the `count()` counter for a particular label.

### `void Console::error(mixed $msg)`
Logs the argument to the console as an error.

### `void Console::group(string $label)`
Creates a new inline group in the console.

### `void Console::group_collapsed(string $label)`
Creates a new collapsed inline group in the console.

### `void Console::group_end()`
Exits the current inline group.

### `void Console::info(mixed $msg)`
Logs the argument to the console as info.

### `void Console::log(mixed $msg)`
Logs the argument to the console.

### `void Console::warn(mixed $msg)`
Logs the argument to the console as a warning.
