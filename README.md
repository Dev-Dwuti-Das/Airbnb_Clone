# 🏡 Airbnb Clone

A full-stack **Airbnb-inspired web application** that allows users to create, browse, and book property listings. Built with **Node.js**, **Express**, **MongoDB**, and **EJS**, this project replicates key features of Airbnb, including **authentication**, **map integration**, **image uploads**, and a **booking system**.

---

## 📸 Screenshots
![Image](https://github.com/user-attachments/assets/00be90a9-b5b3-4d72-8e41-fdb22ac4cd0a)
<img width="1919" height="1057" alt="Image" src="https://github.com/user-attachments/assets/7a273965-333d-4a80-a36b-d769b7afcbc8" />
<img width="1918" height="1074" alt="Image" src="https://github.com/user-attachments/assets/511e05d3-542f-487e-8c02-1d3c39a5aeb0" />
<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/2d6a500d-0c40-42e5-ab01-63055275f31c" />



---

## 🚀 Live Demo  
🌐 **Hosted Link**: [Airbnb Clone](https://airbnb-clone-snm7.onrender.com/listing)

---

## ⚡ Tech Stack
**Backend**  
- [Node.js](https://nodejs.org/) – JavaScript runtime  
- [Express.js](https://expressjs.com/) – Web framework  
- [Mongoose](https://mongoosejs.com/) – MongoDB object modeling  

**Frontend**  
- [EJS](https://ejs.co/) – Templating engine  
- [Bootstrap 5](https://getbootstrap.com/) – UI framework  
- Vanilla JavaScript  

**Database & Cloud Services**  
- [MongoDB Atlas](https://www.mongodb.com/atlas) – Cloud database  
- [Cloudinary](https://cloudinary.com/) – Image storage & hosting  

**Other Tools**  
- [Multer](https://github.com/expressjs/multer) – File upload handling  
- [Mapbox](https://www.mapbox.com/) – Interactive maps  
- [Passport.js](http://www.passportjs.org/) – User authentication  

---

## ✨ Features
- 🔑 **User Authentication & Authorization** – Register, Login, Logout using Passport.js  
- 🏘️ **Listings Management** – Create, Read, Update, and Delete property listings  
- 🗺️ **Map Integration** – Interactive maps powered by Mapbox
- 🔍 **Search Functionality** – Search listings by title, location, or keywords  
- 🖼️ **Image Uploads** – Upload and manage images with Cloudinary & Multer  
- 📅 **Booking System** – Date conflict validation for reservations  
- ⭐ **Review & Rating** – Users can leave reviews and ratings for listings  
- 💻 **Responsive UI** – Clean and mobile-friendly design using Bootstrap 5  
- ☁️ **MongoDB Atlas** – Scalable cloud database for production  
---

## 📂 Project Structure
```
Airbnb_Clone/
├── models/         # Mongoose schemas (User, Listing, Review, etc.)
├── routes/         # Express routes
├── views/          # EJS templates
├── public/         # Static files (CSS, JS, images)
├── utils/          # Utility functions (middleware, validators)
├── app.js          # Main server file
└── package.json    # Dependencies and scripts
```

---

## ⚙️ Installation & Setup
Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dev-Dwuti-Das/Airbnb_Clone.git
   cd Airbnb_Clone
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Create a `.env` file in the project root and add the following:**
```env
# MongoDB Atlas
MONGO_URI=your_new_mongodb_atlas_connection_string

# Cloudinary
CLOUDINARY_CLOUD_NAME=your_new_cloud_name
CLOUDINARY_KEY=your_new_cloud_api_key
CLOUDINARY_SECRET=your_new_cloud_api_secret

# Mapbox
MAPBOX_TOKEN=your_new_mapbox_token

# Express Session
SESSION_SECRET=your_random_session_secret
```

4. **Run the development server**
   ```bash
   npm start
   ```
   
5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```
   
---
## 🛠️ Future Enhancements 
- ✅ Wishlist functionality
- ✅ AI based suggestion
- ✅ AI based listing
 
---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!  
Feel free to fork this repo and submit a pull request.

---

## 📜 License
This project is licensed under the **MIT License** – you’re free to use, modify, and distribute it.

---

### 💡 Developer
Made with ❤️ by [Dev Dwuti Das](https://github.com/Dev-Dwuti-Das)
