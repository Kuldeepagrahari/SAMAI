# SamAI
Here's the complete `README.md` file for your project:  

```markdown
# **ChatGPT Clone - SAM AI**

Welcome to the repository for **SAM AI**, a ChatGPT Clone developed using the **MERN stack**, integrated with **Clerk** for user authentication and **Gemini API** for AI model responses. This application ensures a seamless and consistent user experience with responsive UI and robust backend functionalities.

---

## **Features**

### **Core Functionalities**
1. **Authentication with Clerk:**
   - Login and registration system with email, social login, and OTP verification.
   - User session management powered by Clerk for a secure experience.

2. **AI Chat Responses:**
   - Integrated with the **Gemini API** to provide real-time AI-generated responses.

3. **Chat Storage:**
   - User chats and bot responses are stored securely in **MongoDB**, enabling persistence.

4. **Responsive Design:**
   - Fully responsive UI for a consistent experience across devices.

---

## **Tech Stack**
- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Authentication**: Clerk
- **API Integration**: Gemini API
- **Image Management**: ImageKit.io for optimized image delivery

---

## **Setup Instructions**

### **Prerequisites**
- Node.js and npm installed
- MongoDB database setup
- Clerk account for authentication
- Gemini API key
- ImageKit account for image handling

---

### **Installation**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/chatgpt-clone.git
   cd chatgpt-clone
   ```

2. **Install Dependencies**
   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```

3. **Environment Variables**
   Create a `.env` file in the root directory and add:
   ```plaintext
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   CLERK_FRONTEND_API=your_clerk_frontend_api
   CLERK_API_KEY=your_clerk_api_key
   GEMINI_API_KEY=your_gemini_api_key
   IMAGEKIT_PUBLIC_API_KEY=your_imagekit_public_key
   IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
   ```

4. **Start the Application**
   - Start the backend server:
     ```bash
     npm start
     ```
   - Start the frontend client:
     ```bash
     cd client
     npm start
     ```

---

## **Project Structure**

### **Backend**
- **/models**: MongoDB models for user and chat data.
- **/routes**: API routes for chat and authentication.
- **server.js**: Main server file to handle Express app.

### **Frontend**
- **/src/components**: Reusable React components for UI.
- **/src/pages**: Main pages (Login, Chat, etc.).
- **/src/services**: API call functions.
- **/src/styles**: CSS files for consistent styling.

---

## **Commands**

### **Git Commands**
- Clone the repository:
  ```bash
  git clone https://github.com/yourusername/chatgpt-clone.git
  ```
- Create a new branch:
  ```bash
  git checkout -b feature-branch
  ```
- Stage changes:
  ```bash
  git add .
  ```
- Commit changes:
  ```bash
  git commit -m "Your commit message"
  ```
- Push changes:
  ```bash
  git push origin feature-branch
  ```

### **NPM Commands**
- Install dependencies:
  ```bash
  npm install
  ```
- Start development server:
  ```bash
  npm start
  ```
- Build for production:
  ```bash
  npm run build
  ```

---

## **API Endpoints**

### **User Authentication**
- **POST** `/auth/login`: User login
- **POST** `/auth/register`: User registration

### **Chat**
- **POST** `/api/chat`: Save user message and bot response
- **GET** `/api/chat`: Fetch previous chats for a user

---

## **Screenshots**


### **Chat Interface**
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-6.png)
![alt text](image-7.png)
---

## **Future Enhancements**
1. **Multilingual Support**: Adding more language options for better accessibility.
2. **Voice-to-Text Support**: Enabling users to interact with AI using voice commands.
3. **Dark Mode**: Adding a toggle for dark mode.

## **Contributing**
1. Fork the repository.
2. Create a new feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push the branch:
   ```bash
   git push origin feature-name
   ```
4. Create a pull request describing your changes.


---

## **Contact**
For questions or support, contact:
- **Developer**: Kuldeep Agrahari
- **Email**: kuldeepagrahari9103@gmail.com
- **LinkedIn**: [Kuldeep Agrahari](https://www.linkedin.com/in/kuldeep-agrahari-56b159260)
