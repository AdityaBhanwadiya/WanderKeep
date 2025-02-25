# **Wander Keep**

## 📌 **Description**

Welcome to **Wander Keep**! 

This application is built using **Django, HTML, CSS, JavaScript, Python, and Bootstrap**.

The core idea behind **Wander keep** is to help users save and revisit special locations they have fallen in love with. Often, people find themselves in random but incredible places, and later struggle to remember their exact location. **Wander Keep** aims to solve this by allowing users to save, categorize, and describe locations, ensuring they can always find their favorite spots again.

Users can **add, edit, and delete** places, including details such as names, descriptions, images, and categories. Locations are marked on an interactive map, making it easier to navigate and find saved places.

---

## 🌟 **Distinctiveness & Complexity**

This project stands out because it is **interactive and map-based**, differing from common applications such as search engines, wikis, or social media clones. 

The application integrates:
- **Django** for backend management.
- **JavaScript** for frontend interactions.
- **Mobile responsiveness** for seamless usability across devices.
- **APIs for location services** to enhance user experience.

---

## 🏗 **Features**

### **1. Interactive Map Page**
- Displays a **globe map** with user location capabilities.
- Users can **click to retrieve coordinates and addresses**.
- Option to **save locations** with details like title, description, and category.
- Newly added locations appear dynamically on the map without requiring page reloads.
- Quick deletion of locations directly from the map interface.

### **2. Saved Places Page**
- View and manage all saved places.
- **Filter locations** by category or search by name.
- Edit or delete saved locations with real-time updates.

---

## 📂 **Project Structure**

The project contains two main directories: 

### **1. Django Project (capstone)**
- **settings.py** – Configures project settings.
- **urls.py** – Defines URL patterns for routing.
- **wsgi.py** – Web server gateway interface.

### **2. Django App (wanderkeep)**
- **Static Files** – Contains JavaScript, CSS, and images.
- **Templates** – HTML templates for different pages.
- **Models** – Defines database structure.
- **Views** – Handles logic and interactions.
- **Serializers** – Converts data for frontend integration.
- **URLs** – App-specific routing.

---

## 🔑 **API Keys Setup**

To fully utilize **location-based features**, add API keys in `map.js`:
- **Mapbox API Key** – Required for interactive map rendering ([Get Key](https://docs.mapbox.com/)).
- **Google API Key** – Required for reverse geocoding ([Get Key](https://console.cloud.google.com/)).

---

## 🏆 **Contributions & Support**

Contributions are welcome! Feel free to **fork the repository**, create a pull request, or suggest improvements. 

For issues or questions, please use **GitHub Issues**.

🌍 **Happy Mapping!** 🚀
