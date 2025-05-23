**ZERO WASTE PROJECT**<br>

**Problem Statement**<br>
Every day, massive quantities of edible food are wasted while millions of people remain food-insecure.<br>
This is often due to a lack of coordination between food donors (restaurants, individuals, events) and recipients (NGOs, shelters, etc). <br>
ZeroWaste is a scalable, intelligent web platform designed to bridge this gap using real-time location and managing logistics.<br>

**Objective**<br>
To develop a centralized food donation and rescue platform that:
- Minimizes food wastage
- Empowers real-time connections between donors and receivers
- Leverages technology to automate pickups and manage logistics

**Key Features**<br>
**Donor Panel**
- Register via email
- Post food availability, quantity
- Track donation status (Pending → Accepted → Picked → Verified)
  
**Receiver Panel (NGOs / Volunteers)**
- Role-based registration & verification
- View donations on an interactive map
- Filter by food type, freshness
- Accept or request pickups
- Confirm delivery with optional rating
  
**GeoMap Dashboard**
- Google Maps / OpenStreetMap integrated
- Live pickup routing using Google Directions API

**Tech Stack Used**<br>
Frontend:<br>
- HTML, CSS, JavaScript
- EJS (Embedded JavaScript templates)
  
Backend:<br>
- Node.js
- Express.js
  
Database:<br>
- Firebase Realtime Database (for real-time data sync and scalability)
  
APIs and Services:<br>
- Google Maps API (location display)
- Google Directions API (pickup routing)
- Firebase Authentication
  
**WORKFLOW**<br>
1️⃣ User Registration:<br>
- Donors, receivers register via email/OAuth.<br>
2️⃣ Food Donation Posting (Donor):<br>
- Enter food details, quantity, and donor's address.<br>
3️⃣ Real-Time Visibility (Receiver):<br>
- Nearby NGOs/volunteers see available donations on a live map with filtering options.<br>
4️⃣ Pickup and Routing:<br>
- Once accepted, live pickup route is shown using Google Directions API.<br>


