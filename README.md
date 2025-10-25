# Calcélla Calculator ✨

A beautiful, aesthetic calculator built with HTML, CSS, and JavaScript. Calcélla blends sleek functionality with an elegant, modern interface featuring smooth animations and a minimal color palette.

![Calcélla Calculator](https://img.shields.io/badge/Status-Live-brightgreen)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Features

- **Beautiful UI**: Modern design with glassmorphism effects and smooth animations
- **Fully Functional**: All basic mathematical operations (addition, subtraction, multiplication, division)
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Keyboard Support**: Use your keyboard to interact with the calculator
- **Elegant Animations**: Smooth transitions and hover effects for a delightful user experience
- **Error Handling**: Prevents division by zero and handles edge cases gracefully

## 🚀 Live Demo

Visit the live app: [https://calella.onrender.com](https://calella.onrender.com)

## 📁 Project Structure

```
calella-calculator/
├── index.html       # Main HTML structure
├── styles.css       # Beautiful styling and animations
├── script.js        # Calculator logic and functionality
├── render.yaml      # Render deployment configuration
├── package.json     # Project metadata
└── README.md        # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: Modern styling with animations and glassmorphism
- **JavaScript (ES6+)**: Object-oriented calculator logic
- **Render**: Cloud hosting platform

## 📖 How to Use

1. **Number Buttons**: Click to enter numbers (0-9)
2. **Operation Buttons**: Select an operation (+, −, ×, ÷)
3. **Equals Button**: Calculate the result
4. **AC Button**: Clear everything and start over
5. **DEL Button**: Delete the last entered digit

### Keyboard Shortcuts

- `0-9`: Enter numbers
- `+`, `-`, `*`, `/`: Select operations
- `Enter` or `=`: Calculate
- `Esc` or `C`: Clear all
- `Backspace`: Delete last digit

## 🚀 Deploy to Render

### Prerequisites
- A GitHub account
- Your code pushed to a GitHub repository

### Steps

1. **Push to GitHub**: 
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Calcélla Calculator"
   git branch -M main
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Sign up/Login to Render**: Go to [render.com](https://render.com)

3. **Create New Web Service**:
   - Click "New +" → "Web Service"
   - Connect your GitHub repository
   - Or manually deploy by selecting your repo

4. **Configure Settings**:
   - **Name**: `calella-calculator` (or your preferred name)
   - **Environment**: `Python 3`
   - **Build Command**: `echo "Building..."` (or leave blank)
   - **Start Command**: `python3 -m http.server $PORT`
   - **Plan**: Free

5. **Deploy**:
   - Click "Create Web Service"
   - Wait for deployment (usually 2-5 minutes)
   - Your app will be live at `https://your-app-name.onrender.com`

### Alternative: Using render.yaml

If you have a `render.yaml` file (already included), you can:
1. Go to Render Dashboard
2. Select "New" → "Blueprint"
3. Connect your repository
4. Render will automatically detect and use the configuration

## 💻 Local Development

1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd akkkiii
   ```

2. **Start a local server**:
   ```bash
   # Using Python
   python3 -m http.server 8000
   
   # Or using Node.js
   npx serve
   ```

3. **Open in browser**:
   Visit `http://localhost:8000`

## 🎨 Customization

### Colors
Edit `styles.css` to change the color scheme:
- Background gradient: Lines 14-15
- Button colors: Lines 129-155
- Glass effect: Lines 25-30

### Fonts
Change the font family in `styles.css` line 11:
```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, ...;
```

## 📝 License

This project is open source and available under the MIT License.

## Acknowledgments

- Built with love and attention to detail
- Inspired by modern calculator designs
- Powered by vanilla JavaScript (no frameworks needed!)

## 📧 Contact

Questions or suggestions? Open an issue on GitHub!

---

Made with lots of love by akshaya✨✨
