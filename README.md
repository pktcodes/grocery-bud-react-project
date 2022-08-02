# Grocery Bud 🛍️

> PROD [Live] : https://react-grocery-bud-prod.netlify.app/

#### Grocery Bud consists of a straightforward user interface where there is a

- **Input** box which takes the names of a grocery item and adds it to the list along with the page title *Grocery Bud*.
- Functionality is 
  - By default when the application loads, the input will be empty.
  - Once an item name is provided in the input and click submit, the item gets added to the list with an alert **Item Added To The List**.
  - Every single item added to the list has **`Edit`** and **`Delete`** buttons along with the name.
  - If the user wants to edit an item, the `Edit` button can be clicked which gives an option to rename the item in the input and submit it with an alert **Item Edited**.
  - If the user wants to delete an item, the `Delete` button can be clicked which deletes the item from the list with an alert **Item Removed**.
  - All the items in the cart can be cleared using the **`Clear Items`** button with an alert **Empty List**.
  - **Local storage** has been implemented to persist the data when the user revisits the application and the sorting order of the other items don't get affected when an item is edited or deleted.
- Styles are handled by `index.css`
- To run the project locally, clone the repo, `npm install` to install the dependencies, and `npm start` to start up the development server on default port 3000.

#### Languages
HTML, CSS, JavaScript, ECMAScript, React - Hooks ~ useState, useEffect

#### Packages
[React Icons](https://www.npmjs.com/package/react-icons)

#### Deployment / Hosting
Netlify

---

*Note: I have developed this project ~ [10] as part of React and Projects Course taught by John Smilga.*
