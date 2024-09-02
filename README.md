# Entertainment System Tests

This repository contains a set of unit tests for an entertainment system. The purpose of these tests is to ensure that key functionalities of the system are working as expected. The tests are written using Python's `unittest` framework.

## Overview

The `EntertainmentSystemTests` class includes several test cases designed to validate the behavior of various components in the entertainment system. The tests focus on:

1. Verifying that the daily movie is licensed.
2. Ensuring that the Wi-Fi is enabled.
3. Checking if the maximum display brightness meets the expected value.
4. Confirming that the device temperature remains within a safe range.

## Tests

### 1. `test_movie_license`

- **Purpose:** Verify that the daily movie provided by the entertainment system is among the list of licensed movies.
- **Method:** Retrieves the daily movie and the list of licensed movies and checks if the daily movie is included in the licensed list.

### 2. `test_wifi_status`

- **Purpose:** Ensure that the Wi-Fi is enabled on the device.
- **Method:** Checks the status of the Wi-Fi and asserts that it is enabled (`True`).

### 3. `test_maximum_display_brightness`

- **Purpose:** Validate that the maximum display brightness is set to the expected level.
- **Method:** Retrieves the maximum display brightness and asserts that it is approximately 400 units.

### 4. `test_device_temperature`

- **Purpose:** Confirm that the device temperature is within a safe operational range.
- **Method:** Retrieves the device temperature and asserts that it is less than 35 degrees Celsius.

## Learning Outcomes

By working with this code, you will:

1. **Understand Unit Testing:** Gain practical experience with unit testing in Python using the `unittest` framework.
2. **Test Different Functionalities:** Learn how to write tests for various system functionalities including licensing, device status, and performance metrics.
3. **Assert Statements:** Develop skills in using assert statements to validate expected outcomes in test cases.
4. **Error Handling:** Understand how to identify and address issues in system components based on test results.
5. **Automation in Testing:** See how automated tests can help in maintaining the reliability and stability of software systems.

## Running the Tests

To execute the tests, simply run the following command in your terminal:

```bash
python -m unittest <name_of_this_file>.py
```

Ensure that the `entertainment` module is available in your Python environment as it is required for the tests.

## Dependencies

- Python 3.x
- `unittest` module (included in standard library)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
