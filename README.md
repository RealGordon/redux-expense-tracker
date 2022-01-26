# Expense Tracker
This project is a budgeting and expense tracking app— with **React** and **Redux**.
The app allows you to set budgets for various categories, such as food and transportation, and track transactions in those categories.
It then sums your spending in each category to calculate the amount of money that remains to be spent.


Sample Redux store state:
```javascript
{
  budgets: [ 
    { category: 'housing', amount: 400 },
    { category: 'food', amount: 100 },
    ...
  ],
  transactions: {
    housing: [ 
      { 
        category: 'housing', 
        description: 'rent', 
        amount: 400, 
        id: 123 
      }
    ],
    food: [ 
      { 
        category: 'food', 
        description: 'groceries on 1/12/2021', 
        amount: 50, 
        id: 456 
      },
      { 
        category: 'food', 
        description: 'dinner on 1/16/2021', 
        amount: 12, 
        id: 789 
      },
    ]
  }
 
 
}
```
