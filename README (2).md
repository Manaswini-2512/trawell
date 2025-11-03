# 🧭 Trawell  

A web-based tourism and culture platform built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.  
**Trawell** connects travelers with local artisans, destinations, and cultural experiences—encouraging **sustainable tourism** and **handicraft promotion** through a single digital platform.  

---

## Features  
- Location-based discovery of artisans, crafts, and tourist spots.  
- User and artisan authentication with profile management.  
- Craft listings with images, pricing, and detailed descriptions.  
- Booking and interaction options for travelers.  
- Admin dashboard for approving artisans and managing data.  
- Responsive UI design for both mobile and web users.  
- Integration with Google Maps API for location visualization.  
- Promotes cultural tourism and supports local craftsmanship.  

---

## Requirements  
- **Node.js** (v16 or above)  
- **MongoDB** (local or cloud)  
- **npm** (Node package manager)  
- **Google Maps API Key**  

---

## Install locally (Windows)  
```powershell
# open PowerShell in the project folder
git clone https://github.com/yourusername/trawell.git
cd trawell

# Backend setup
cd backend
npm install
# Create .env file with:
# MONGO_URI=your_mongodb_uri
# JWT_SECRET=your_secret
# PORT=5000
npm run dev

# Frontend setup (in a new terminal)
cd ../frontend
npm install
npm start
```

---

## Run  
Once both frontend and backend servers are running,  
open your browser and go to:  
```bash
http://localhost:3000
```

---

## Recommended repo contents before pushing to GitHub  
- `backend/` (Node.js + Express server)  
- `frontend/` (React app)  
- `README.md` (this file)  
- `.env.example` (sample environment file)  
- `.gitignore` (ignore `node_modules`, `.env`, and build files)  

---

## Technology Stack  
- **Frontend:** React.js, HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **APIs:** Google Maps API, RESTful APIs  
- **Tools:** Git, GitHub, Postman, Figma  
