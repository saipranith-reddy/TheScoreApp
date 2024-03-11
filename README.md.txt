# ScoreAppTest Automation

This project contains automated tests for theScore mobile application using the Appium Framework.

## Setup

### Prerequisites
- Java Development Kit (JDK) 11 or higher
- Appium 2.x
- Android Emulator or Physical Device

### Dependencies
- Appium Java Client
- Selenium WebDriver

### Installation
1. Clone this repository to your local machine.
2. Ensure Appium server is running either locally or on a cloud testing platform.
3. Install the necessary dependencies using Maven or Gradle.

## Running Tests
1. Start the Appium server.
2. Run the `ScoreAppTest` class located in the `src/test/java` directory.

## Test Scenario
- The test automates the following steps:
  1. Opens a league, team, or player page.
  2. Verifies the expected page opens correctly.
  3. Taps on a sub-tab and verifies correct navigation and data display.
  4. Verifies back navigation returns to the previous page correctly.

## Test Implementation
- The test cases are implemented in Java using the Appium Framework.
- Assertions are used to verify the expected behavior at each step.
- Placeholder methods for verification are provided in the test class (`ScoreAppTest`) and should be replaced with actual verification logic.

## Additional Notes
- Ensure proper device setup and configuration for testing on an emulator or physical device.
- Replace placeholder element IDs in the test code with actual IDs from theScore app.
- Update verification logic in the test code to match the behavior of theScore app.

For any issues or questions, please contact [Your Name] <your.email@example.com>.
