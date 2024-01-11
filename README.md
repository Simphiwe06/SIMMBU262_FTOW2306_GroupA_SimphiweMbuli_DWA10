# Tally Count App

This is a simple web application that serves as a tally counter. The app allows users to increment and decrement a counter and reset it to zero.

## User Stories

### Scenario: Increment the counter by one
- **GIVEN** the tally counter app is open
- **AND** the counter is at 0
- **WHEN** I click the "Add" button
- **THEN** the counter should display 1

### Scenario: Decrement the counter by one
- **GIVEN** the tally counter app is open
- **AND** the counter is at 1
- **WHEN** I click the "Subtract" button
- **THEN** the counter should display 0

### Scenario: Resetting the Tally Counter
- **GIVEN** the tally counter app is open
- **AND** the counter value is 10
- **WHEN** I click on the "Reset" button
- **THEN** the counter value should change to 0
- **AND** a confirmation message should be displayed that the counter has been reset

## Technologies Used

- HTML
- CSS
- JavaScript
- Shoelace (for button styling)

## Setup

To run this project locally, follow these steps:

1. Clone the repository.
2. Open the `index.html` file in your web browser.

## How to Use

1. Press the "+" button to increment the counter.
2. Press the "-" button to decrement the counter.
3. Press the "Reset" button to reset the counter to zero.

## Notes

This project is meant for learning JavaScript and is not intended for production use.

## Acknowledgements

Inspired by the Tally Count app available at [tallycount.app](https://tallycount.app/).

https://simphiwe-tally-app.netlify.app/
