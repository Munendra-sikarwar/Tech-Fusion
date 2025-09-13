# SharingPlate

SharingPlate is a web platform designed to connect NGOs with donors who have surplus food, enabling them to efficiently collect and distribute food to those in need. By leveraging AI and modern web technologies, SharingPlate aims to reduce food wastage while addressing hunger and improving community welfare.

---

## Features

- **Event Management (CRUD)**: NGOs can create, retrieve, update, and delete food donation events. Each event includes:  
  - **Location**: Longitude and latitude  
  - **Timing**: Event date and time  
  - **Quantity**: Amount of food available  
  - **Notes**: Additional information for the event  
  - **Integrate**: real-time map updates for better event tracking.


- **Authentication & Verification**:  
  - NGOs can register using **email, phone, and optionally photo**.  
  - NGOs may also use the platform **without authentication** if they prefer.  
  - Donors can list surplus food **without verification**.  

- **Food Listing & Search**: Search food events by name, location, quantity, and more.  
- **Spam Reporting**: NGOs can flag suspicious or spam listings.  
- **Dashboard**: Centralized dashboard for NGOs and donors to track events.  
- **AI-Powered Visualization**:  
  - Heatmaps showing locations with higher demand for donations.  
  - Future enhancement: Predictive heatmaps indicating areas with potential food wastage. 
  
- **Leaderboards & Incentives**:  
  1. **Donor Leaderboard**: Donors are ranked according to the volume of food donated and can receive advertisement benefits, motivating active participation.  
  2. **NGO Leaderboard**: NGOs are ranked based on how much food they pick up and distribute. Top NGOs can receive funding or additional support.  
  3. **Funding Acceptance**: NGOs can accept funds to enhance their operations and increase food distribution efficiency.  
 

---

## Tech Stack

- **Backend**: Spring Framework, Spring Security, JWT Authentication  
- **Database**: PostgreSQL, PostGIS  
- **Frontend**: HTML, CSS, JavaScript  
- **API Management**: API Pagination, API Versioning  
- **AI & Data Visualization**: Python, scikit-learn, matplotlib, Folium  

---

## Usage

- NGO Interface: Sign up with email and phone (optional photo), create and manage food donation events, search for available food, flag spam listings, and view the dashboard. NGOs may also operate without authentication.

- Donor Interface: Add surplus food details without verification, update event status once food is collected.

- AI Visualization: View heatmaps showing where NGOs can donate food efficiently.


## Future Improvements

- Implement predictive AI models for food wastage hotspots.

- Add push notifications for urgent donation requests.


## Contributors

Suyash Chauhan
Divya
Lucky
Munendra Sikarwar
Rishabh Saraswat