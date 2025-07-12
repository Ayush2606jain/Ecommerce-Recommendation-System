# 🛍️ Ecommerce Recommendation System

A modern, AI-powered ecommerce recommendation system built with Flask, featuring beautiful glassmorphism UI, interactive settings, and machine learning-based product recommendations.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Flask](https://img.shields.io/badge/Flask-2.0+-green.svg)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--learn-orange.svg)
![UI](https://img.shields.io/badge/UI-Glassmorphism-purple.svg)

## ✨ Features

### 🎨 Beautiful Modern UI
- **Glassmorphism Design**: Stunning frosted glass effects on cards and modals
- **Animated Gradient Background**: Dynamic, smooth color transitions
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Interactive Settings**: Customizable themes, fonts, and colors

### 🧠 AI-Powered Recommendations
- **Content-Based Filtering**: Uses TF-IDF vectorization and cosine similarity
- **Product Similarity**: Finds similar products based on descriptions and tags
- **Smart Search**: Enter any product name to get personalized recommendations
- **Configurable Results**: Choose how many recommendations to display

### ⚙️ Advanced Settings Panel
- **Theme Customization**: Dark mode, green mode, or custom color themes
- **Random Color Generator**: One-click random theme color selection
- **Font Selection**: Choose from multiple modern fonts (Default, Montserrat, Poppins, Lobster)
- **Zoom Controls**: Adjust page zoom for better accessibility
- **Reset Functionality**: Easy reset to default settings

### 🔐 User Management
- **User Registration**: Sign up with username, email, and password
- **User Authentication**: Secure sign-in system
- **Session Management**: Persistent user sessions

## Images
<img width="1893" height="921" alt="Screenshot 2025-07-12 154817" src="https://github.com/user-attachments/assets/3a69e2e4-f67c-41a4-b85f-0b0db44b83ce" />
<br><br>
<img width="1903" height="914" alt="Screenshot 2025-07-12 154849" src="https://github.com/user-attachments/assets/86834a6f-319a-4b7a-8c9b-b09f995ca8ee" />
<br><br>
<img width="615" height="659" alt="Screenshot 2025-07-12 154943" src="https://github.com/user-attachments/assets/86cb92e6-7cb0-4ce3-9280-441c9be9129f" />
<br><br>
<img width="1879" height="904" alt="Screenshot 2025-07-12 155108" src="https://github.com/user-attachments/assets/6d2b8cc0-6663-4815-9bf8-3182b9e16d53" />
<br><br>


## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Step 1: Clone the Repository
```bash
git clone https://github.com/Ayush2606jain/Ecommerce-Recommendation-System.git
cd Ecommerce-Recommendation-System
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Run the Application
```bash
python app.py
```

### Step 4: Access the Application
Open your browser and go to: `http://127.0.0.1:5000`

## 📁 Project Structure

```
Ecommerce-Recommendation-System/
├── app.py                          # Main Flask application
├── requirements.txt                # Python dependencies
├── clean_data.csv                  # Processed product data
├── trending_products.csv           # Trending products data
├── static/
│   ├── style.css                   # Custom CSS with glassmorphism
│   ├── v.mp4                       # Background video
│   └── img/                        # Product images
├── templates/
│   ├── index.html                  # Home page with trending products
│   └── main.html                   # Recommendation search page
└── README.md                       # This file
```

## 🎯 How to Use

### 1. Home Page
- View trending products with beautiful cards
- Watch the animated background video
- Access settings and user authentication

### 2. Recommendation System
- Click "Go To Main Page" to access recommendations
- Enter a product name in the search box
- Choose the number of recommendations (1-10)
- Click "Search" to get AI-powered recommendations

### 3. Settings Panel
- Click the "Settings" icon in the navigation
- Customize your experience:
  - **Theme**: Choose from Dark, Green, or Custom colors
  - **Random Color**: Generate a random theme color
  - **Font**: Select from multiple modern fonts
  - **Zoom**: Adjust page zoom level
  - **Reset**: Return to default settings

## 🛠️ Technologies Used

### Backend
- **Flask**: Web framework for Python
- **SQLAlchemy**: Database ORM
- **Scikit-learn**: Machine learning library for recommendations
- **Pandas**: Data manipulation and analysis

### Frontend
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with glassmorphism effects
- **JavaScript**: Interactive functionality
- **Bootstrap 4**: Responsive grid system
- **Font Awesome**: Beautiful icons

### Machine Learning
- **TF-IDF Vectorization**: Text feature extraction
- **Cosine Similarity**: Product similarity calculation
- **Content-Based Filtering**: Recommendation algorithm

## 🎨 UI/UX Features

### Glassmorphism Design
- Frosted glass effects on cards and modals
- Subtle shadows and transparency
- Modern, elegant appearance

### Animated Background
- Smooth gradient color transitions
- Dynamic background animation
- Professional visual appeal

### Interactive Elements
- Hover effects on cards and buttons
- Smooth transitions and animations
- Responsive design for all devices

## 📊 Data Sources

The system uses Walmart product data including:
- Product names and descriptions
- Brand information
- Review counts and ratings
- Product categories and tags
- Image URLs

## 🔧 Customization

### Adding New Themes
1. Modify the `applySettings()` function in `index.html`
2. Add new theme options to the settings modal
3. Update CSS variables for consistent theming

### Adding New Fonts
1. Import new fonts in `style.css`
2. Add font options to the font selector
3. Update the JavaScript font application logic

### Modifying Recommendations
1. Adjust the `content_based_recommendations()` function in `app.py`
2. Modify TF-IDF parameters for different results
3. Add new similarity metrics if needed

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Ayush Jain**
- GitHub: [@Ayush2606jain](https://github.com/Ayush2606jain)


## 🙏 Acknowledgments

- Walmart for providing the product dataset
- Flask community for the excellent web framework
- Scikit-learn team for the machine learning tools
- Bootstrap team for the responsive CSS framework

## 📞 Support

If you have any questions or need help with the project, feel free to:
- Open an issue on GitHub
- Contact me directly through GitHub
- Check the documentation in the code comments

---

⭐ **Star this repository if you found it helpful!** ⭐ 
