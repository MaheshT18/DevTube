# DevTube - Your Video Platform

Welcome to **DevTube**, a modern video streaming platform that empowers you to create, manage, and share videos with ease. Dive in and start building your video community today!

---

## 🌟 Why DevTube?

- **Effortless Channel Management:** Create and update your channel with a unique handle.
- **Seamless Video Uploads:** Upload videos via Bunny CDN using TUS protocol with real-time status updates.
- **Secure Authentication:** Enjoy safe login with Google OAuth.
- **Live Engagement:** Connect with viewers through real-time notifications and interactive comments.
- **Smart Tagging:** Organize content effortlessly with our tagging system.


---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express, MongoDB (Mongoose)
- **Frontend:** EJS, CSS, JavaScript
- **Authentication:** Passport (Google OAuth)
- **File Uploads:** Bunny CDN & TUS, Multer, ImageKit
- **Real-Time:** Socket.io & Webhooks
- **Utilities:** Dotenv, custom middleware, and utility helpers

---

## 🚀 Quick Start

1. **Clone the Repository**
    ```bash
    git clone (https://github.com/MaheshT18/DevTube)
    cd DevTube
    ```

2. **Install Dependencies**
    ```bash
    npm install
    ```

3. **Configure Environment Variables**  
   Copy the provided `example.env` file to create your own `.env` file:
    ```bash
    cp example.env .env
    ```
   Then update the file with your specific configuration:
    ```env
    # Environment Configuration
    NODE_ENV=development

    # Server Configuration
    SERVER_PORT=3000
    HOST_URL=

    # Database Configuration
    MONGODB_URI=mongodb://<username>:<password>@<host>:<port>/<database>

    # Google OAuth Configuration
    GOOGLE_CLIENT_ID=your_google_client_id
    GOOGLE_CLIENT_SECRET=your_google_client_secret

    # ImageKit Configuration
    IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
    IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
    IMAGEKIT_URL_ENDPOINT=https://ik.imagekit.io/yourid/

    # Bunny.net Configuration
    BUNNY_API_KEY=your_bunny_api_key
    BUNNY_LIBRARY_ID=your_bunny_library_id

    # Bunny.net CDN Configuration
    BUNNY_CDN_HOSTNAME=your_bunny_cdn_hostname
    BUNNY_TOKEN_KEY=your_bunny_token_key
    ```
   *Keep it secure! 🔒*

4. **Launch DevTube**
    ```bash
    npm start
    ```
   Visit [http://localhost:3000/] to start streaming.

---

## 🤝 Contributing

- Fork the repo, create your branch, and submit a pull request.
- Your contributions help improve DevTube for everyone!

---

## 📫 Get in Touch

- **LinkedIn:** (https://www.linkedin.com/in/maheshtolanur/)  
- **Email:** (tolanurmahesh085@gmail.com)

---
## 🎬 Project Demo Video

Watch the working demo of **DevTube** in action! 

https://github.com/user-attachments/assets/4399e355-fd98-4a94-bb31-f2fb1e144454

---

If you enjoy DevTube, please ⭐ the repo and share it with your network.

---

### Made with ❤️ by [Mahesh Tolanur]
