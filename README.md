## ATM Improvements
Learning Outcomes Addressed:

Implement user-friendly UI and React components
Manage state of various UI elements
Validate form content in conjunction with state of other components
Practice communicating project specifications
Practice communicating technical decisions you made

## Improvements made
Added whitespace around form
Added background color around the ATM controls
Changed titles and labels to make more sense
Renamed state called "totalState" to "balance"
Renamed state called "deposit" to "amount" (made more sense to "Widraw an amount" than to "Withdraw a deposit")
Added extra validation to prevent over-withdrawing (submit gets disabled when action is Withdrawal and balance is zero).