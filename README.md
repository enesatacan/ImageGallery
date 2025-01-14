# 🚀 Daily JavaScript App - 17: Horizontal Scroll Image Gallery  
This repository is part of my Daily JavaScript Coding Challenge to build one JavaScript project every day. 🌟 The goal is to refine my JavaScript skills 🧠 while fostering consistency in coding. 💻✨  

---

## 🌟 Features  

### 🔄 **Smooth Horizontal Scrolling**  
This project introduces a horizontal scrolling gallery that allows users to navigate through items effortlessly using:  
- **Mouse Wheel**: Users can scroll horizontally by using their mouse wheel.  
- **Navigation Buttons**: `Back` and `Next` buttons enable smooth navigation by moving the gallery left or right.  

### 🛠 **Dynamic Behavior**  
- **Responsive Scrolling**: The gallery responds to user interactions and adjusts scrolling behavior accordingly.  
- **Smooth Animation**: The navigation buttons implement smooth scrolling for an enhanced user experience.  

---

## 🖥️ How It Works  

### 🔧 Scrolling Logic:  

1. **Mouse Wheel Scrolling**:  
   - Listens to the `wheel` event on the gallery.  
   - Converts vertical scrolling (`deltaY`) into horizontal scrolling by adjusting `scrollLeft`.  

2. **Button Navigation**:  
   - **Next Button**: Moves the gallery 900px to the right with smooth animation.  
   - **Back Button**: Moves the gallery 900px to the left with smooth animation.  

3. **Smooth Scrolling**:  
   - Utilizes the `scrollBehavior` property to enable smooth transitions when buttons are clicked.  

---

## 🛠 Technologies Used  

- **HTML5**  
- **CSS3**  
- **JavaScript**  

---

## 🖥️ Installation  

1. Clone the repository:  
   ```bash  
   git clone [https://github.com/enesatacan/ImageGallery
   ```  

2. Open the project in your favorite code editor.  

3. Serve the project locally or open the `index.html` file directly in your browser to explore the scrolling functionality.  

---

## 💡 Future Enhancements  

- Add keyboard navigation support (e.g., arrow keys for scrolling).  
- Implement a drag-to-scroll feature for touch devices.  
- Include animations for better visual feedback during scrolling.  
- Add support for infinite scrolling to loop the gallery items seamlessly.  

---

![image](https://github.com/user-attachments/assets/9e750b9d-ad30-44c1-bf9a-f213312a65c8)
