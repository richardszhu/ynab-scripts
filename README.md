# ynab-cli
Misc. automations for YNAB

# Commands
`token <personal_access_token>`
- Sets the YNAB personal access token needed to use the API.

`del-token`
- Deletes the YNAB personal access token if it was set.

`budget`
- Shows all budgets and lets user set a budget to perform actions on.

`total-churn`
- Finds all transactions that are marked as churn transactions, and finds their sum. A transaction is marked by adding `#churn` to its memo.
