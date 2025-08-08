# ⭐ Glassmorphism Rating UI (React)

A sleek **React rating component** featuring **glassmorphism styling**, **Google Fonts**, and a **classy turquoise gradient** background.

![Preview](screenshot.png) <!-- Optional screenshot placeholder -->

## ✨ Features
- **React component structure** for easy reuse  
- **Glassmorphism design** with blur effects & transparency  
- **Responsive UI** for desktop & mobile  
- **Interactive star rating** system with state handling  
- **Custom Google Fonts** (Nunito, Quicksand, Baloo 2)  
- **Elegant turquoise gradient** background  

## 📂 Project Structure
src/
├── components/
│ ├── RatingContainer.jsx # Main rating box with glassmorphism
│ ├── Stars.jsx # Star rating logic
│ ├── Modal.jsx # Feedback modal
│ └── Button.jsx # Reusable button component
├── App.jsx # Root component
├── index.js # Entry point
├── styles.css # Global styles

markdown
Copy
Edit

## 🛠 Technologies Used
- **React** (Functional components, hooks)
- **CSS3** (Glassmorphism, gradients, flexbox)
- **JavaScript (ES6+)**
- **Google Fonts** (Nunito, Quicksand, Baloo 2)

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/rating-ui-react.git
cd rating-ui-react
2️⃣ Install dependencies
bash
Copy
Edit
npm install
3️⃣ Start the development server
bash
Copy
Edit
npm start
Then open http://localhost:3000 in your browser.

🎨 Customization
Background Gradient: Update styles.css:

css
Copy
Edit
background: linear-gradient(135deg, #0abfbc, #2c6975, #2a9d8f);
Glassmorphism Effect: Tweak backdrop-filter, opacity, and border in .rating-container.

📜 License
This project is licensed under the MIT License.