<h1 align="center">Hi 👋, I'm Salik</h1>
<h3 align="center">MERN Stack Developer | Full Stack Web Developer</h3>

---

## 🚀 About Me

- 💻 I build full-stack web applications using the MERN Stack  
- 🔐 Experienced in authentication & REST APIs  
- 🌱 Currently improving my backend & system design skills  
- 🎯 Goal: Become a professional Full Stack Developer  

---

## 🛠️ Tech Stack

### 💻 Frontend
- HTML5
- CSS3
- JavaScript (ES6+)
- React.js
- Tailwind CSS / Bootstrap

### ⚙️ Backend
- Node.js
- Express.js
- REST APIs
- JWT Authentication

### 🗄️ Database
- MongoDB
- MongoDB Atlas

### 🛠 Tools & Platforms
- Git & GitHub
- VS Code
- Postman
- Vercel
- Render

---

## 🔥 Featured Projects

### 📝 Smart Task Manager
A full-stack task management app with authentication and task status tracking.  
🔗 Live Demo: (Add Link)  
📂 Repo: (Add Link)

---

### 🛒 Mini E-Commerce Store
Full-stack shopping application with cart & admin panel.  
🔗 Live Demo: (Add Link)  
📂 Repo: (Add Link)

---

### 💬 Real-Time Chat App
Socket.io based real-time messaging app with authentication.  
🔗 Live Demo: (Add Link)  
📂 Repo: (Add Link)

---

import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { BarChart, Bar, XAxis, YAxis, Tooltip, ResponsiveContainer } from "recharts";
import { motion } from "framer-motion";

const data = [
  { name: "Jan", users: 40 },
  { name: "Feb", users: 55 },
  { name: "Mar", users: 75 },
  { name: "Apr", users: 60 },
  { name: "May", users: 90 },
];

export default function AdminDashboard() {
  return (
    <div className="min-h-screen bg-gray-100 p-6">
      <motion.h1
        initial={{ opacity: 0, y: -20 }}
        animate={{ opacity: 1, y: 0 }}
        className="text-3xl font-bold mb-6"
      >
        📊 Admin Dashboard
      </motion.h1>

      {/* Stats Cards */}
      <div className="grid grid-cols-1 md:grid-cols-3 gap-6 mb-8">
        <Card className="rounded-2xl shadow-md">
          <CardContent className="p-6">
            <h2 className="text-lg font-semibold">Total Users</h2>
            <p className="text-2xl font-bold mt-2">1,240</p>
          </CardContent>
        </Card>

        <Card className="rounded-2xl shadow-md">
          <CardContent className="p-6">
            <h2 className="text-lg font-semibold">Revenue</h2>
            <p className="text-2xl font-bold mt-2">$8,450</p>
          </CardContent>
        </Card>

        <Card className="rounded-2xl shadow-md">
          <CardContent className="p-6">
            <h2 className="text-lg font-semibold">Active Sessions</h2>
            <p className="text-2xl font-bold mt-2">320</p>
          </CardContent>
        </Card>
      </div>

      {/* Chart Section */}
      <Card className="rounded-2xl shadow-md">
        <CardContent className="p-6">
          <h2 className="text-xl font-semibold mb-4">Monthly User Growth</h2>
          <div className="h-80">
            <ResponsiveContainer width="100%" height="100%">
              <BarChart data={data}>
                <XAxis dataKey="name" />
                <YAxis />
                <Tooltip />
                <Bar dataKey="users" />
              </BarChart>
            </ResponsiveContainer>
          </div>
        </CardContent>
      </Card>

      {/* Action Section */}
      <div className="mt-8 flex gap-4">
        <Button className="rounded-2xl">Add User</Button>
        <Button variant="outline" className="rounded-2xl">View Reports</Button>
      </div>
    </div>
  );
}


## 🌍 Connect With Me

- 💼 Upwork: (https://www.upwork.com/freelancers/~0179c65d8c37ab2133)
- 🌐 Portfolio: (Add Link)
- 📧 Email: (Add Email)

---

⭐ From [Salik](https://github.com/Salik-Axi)
