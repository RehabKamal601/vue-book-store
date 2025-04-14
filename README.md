Book Store Project - README
📖 Project Overview
A Vue.js-based book store application with shopping cart functionality that allows users to:

Browse a collection of books

Add/remove books from their cart

View cart contents and total price

Toggle between store and cart views

🛠️ Technologies Used
Frontend: Vue.js 3, Bootstrap 5

Styling: Custom CSS

Currency Formatting: Intl.NumberFormat (SAR)

📂 File Structure
Copy
book-store/
├── index.html          # Main HTML file
├── books.js            # Book data (array of book objects)
├── README.md           # This documentation file

🔧 Setup Instructions
Clone the repository

Open index.html in a web browser

No server/dependencies needed - runs client-side only

🎨 Key Features
Responsive Book Cards:

Cover images

Title, author, price

Stock indicators (color-coded)

"Add to Cart" button

Shopping Cart:

Quantity adjustment (+/-)

Item removal

Subtotal, tax, and grand total calculation

Empty cart state handling

Navigation:

Toggle between store and cart views

Cart item counter in header

📝 Book Data Structure
Each book in books.js follows this format:

javascript
Copy
{
  id: 'B001',
  ISBN: '978-3-16-148410-0',
  name: 'Book Title',
  category: 'Category',
  author: 'Author Name',
  price: 29.99,
  pages: 300,
  instock: 10,
  description: "Book description...",
  image: 'url/to/cover.jpg'
}
💡 Customization Options
To add more books:

Add new objects to the books array in books.js

To change currency:

Modify the currencyFormatter method in the Vue app

To adjust styling:

Edit the CSS in the <style> section of index.html

🌟 Future Enhancements
LocalStorage persistence for cart

Book search/filter functionality

User rating system

Checkout process

📜 License
MIT License - Free to use and modify


