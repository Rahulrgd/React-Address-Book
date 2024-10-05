# React Task ⚛️

## Description
Try to finish as much TODO's as possible. These are found within the React app codebase. When you view the `/src` folder you will find an application for users that want to create their own addressbook (also shown in the video above). But as mentioned before there are some TODO's to be completed in order to make the application work as expected.

In order to start this assignment you need to:
- ⬇️ Clone this repository
- 🌲 Create a separate branch called `feat/todo-assignment`
- 👨‍💻 Open up your preferred editor (mine is VS Code)
- 🏃🏻‍♂️ Run `npm install` and then `npm start`
- 🔎  Search for all `TODO:` strings within the `/src` folder and start building!

> Note: You will find some Bonus TODO's. These are not mandatory for completing this assignment. Feel free to flex your programming skills 💪

## TODO's 
Here is a list of all the TODO's to make life a bit easier:

### Web3 (Must do)
- [ ] [Substreams Uniswap v3 Ethereum](https://thegraph.com/explorer/subgraphs/HUZDsRpEVP2AvzDCyzDHtdc64dyDxx8FQjzsmqSg4H3B)
- [ ] Pick top 5 pools and display all the details in a table
    - Pool
    - Tokens of pool
    - Reserve of token
    - Price of token
    - Top liquidity provider
    - Daily volume
- [ ] Pick top (on the basis of price) 5 tokens and display all the details in a table
    - Token name and symbol
    - Current and total supply
    - Is standard ERC20? Or deflationary?
    - Transaction count
    - Volume in USD
    - Total value locked in USD
    - Day data
- [ ] Deploy your own ERC20 standard token and prepare UI around
    - Show user balance
    - User can perform transfer of tokens
    - A table to show transaction details by user

### React
- [ ] Write a custom hook to set form fields in a more generic way.
- [ ] Fetch addresses based on houseNumber and zipCode.
- [ ] Create generic `<Form />` component to display form rows, legend and a submit button.
- [ ] Create an `<ErrorMessage />` component for displaying an error message.
- [ ] Add a button to clear all form fields. Button must look different from the default primary button, see design.
- [ ] Add conditional classNames for `primary` and `secondary` variant in `<Button />` component

### Redux
- [ ] Prevent duplicate addresses.
- [ ] Write a state update which removes an address from the addresses array.

### Styling (Optional)
- [ ] Add the 'Roboto' font from Google fonts and add it as a global CSS var called `--font-primary`.
- [ ] Make application responsive. It is already for the most part, but it is not optimal for smaller screens.
- [ ] Create separate styles for .primary and .secondary variants of the button component.

## Submitting assignment
You can submit your assignment by creating a merge request for your `feat/todo-assignment` branch. That's it, good luck! 🚀




