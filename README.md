# 🏥 Doctor Appointment Booking System

A full-stack web application that allows patients to view doctor profiles, check real-time availability, and book appointments seamlessly.

## 🚀 Features

- 🧑‍⚕️ Browse doctor profiles with detailed information (name, specialization, degree, experience, fees)
- 📅 View dynamically generated available slots (next 7 days, real-time filtered)
- ⏰ Prevent double bookings by disabling already booked slots
- 🔐 Secure login and token-based authentication for booking
- 📄 View user appointments after booking
- 🔍 Related doctor recommendations based on specialization
- 💻 Responsive UI built for both desktop and mobile

## 🛠️ Tech Stack

**Frontend:**
- React.js
- React Router DOM
- Axios
- Tailwind CSS
- React Toastify

**Backend:**
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT Authentication

## 🔗 Live Demo

https://doctor-appointment-booking-application-frontend.vercel.app/

## 🧩 How It Works

1. **User visits doctor profile** – views image, name, specialty, experience, fees, and about section.
2. **Real-time slot generation** – next 7 days of slots shown (10 AM to 9 PM, 30-min intervals).
3. **Slot filtering** – removes already booked times using data from backend.
4. **Booking** – authenticated users can book a slot by selecting date and time.
5. **Confirmation** – booking saved to DB and user redirected to "My Appointments".



## 🛠 Installation & Setup

### **Clone the repository**

git clone https://github.com/your-username/your-repo.git

cd your-repo

📦 Backend Setup

cd backend

npm install

Create a .env file:

PORT=5000

MONGO_URI=your_mongodb_url

JWT_SECRET=your_secret

CLOUDINARY_CLOUD_NAME=xxx

CLOUDINARY_API_KEY=xxx

CLOUDINARY_API_SECRET=xxx

RAZORPAY_KEY_ID=xxx

RAZORPAY_KEY_SECRET=xxx

Start backend:

npm run dev

💻 Frontend Setup

cd frontend

npm install

npm run dev

## screenshots

# Register

<img width="1213" height="431" alt="image" src="https://github.com/user-attachments/assets/53e920d3-7d07-41df-86a3-81db63197b6c" />


# Home

<img width="1209" height="1423" alt="image" src="https://github.com/user-attachments/assets/b05ef446-d09f-4c74-babc-6ae3a7bdbf15" />

# All Doctors

<img width="1165" height="1165" alt="image" src="https://github.com/user-attachments/assets/8633100a-8672-4019-9c37-2eafc3dc3dd5" />

# Appointment booking

<img width="1216" height="506" alt="image" src="https://github.com/user-attachments/assets/b208c37c-b29f-4517-a61e-d8e6f7d2e246" />

# My Appointments

<img width="1158" height="236" alt="image" src="https://github.com/user-attachments/assets/7bbec679-b01e-4455-80ef-1ac3f8b88866" />




🤝 Contributing

Pull requests are welcome.

Follow a clean commit style and open issues when necessary.

📜 License

This project is licensed under the MIT License.

