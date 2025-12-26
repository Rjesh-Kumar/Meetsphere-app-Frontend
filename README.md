# MeetSphere Frontend

React-based meetup events browser with search, filtering, and detailed event views. Connects to MeetSphere API backend.

## Demo Link

[Live Demo]()

## Quick Start
git clone: https://github.com/Rjesh-Kumar/Meetsphere-app-Frontend.git

cd meetsphere-frontend

npm install

npm run dev


## Technologies

- React 19 
- React Router 
- Vite 
- Bootstrap 5 
- Bootstrap Icons 

## Features

**Event List (/):**  
- Browse all meetup events in card layout  
- Real-time search by title/tags  
- Filter by type (Online/Offline/Both)  
- Click card to view event details  

**Event Details (/events/:id):**  
- Full event information (title, description, venue, price)  
- Speakers list with photos/roles  
- Event timing (IST), tags, dress code, age restrictions  
- Back to list navigation  

## API Reference

**Backend:** `https://meetup-app-backend-chi.vercel.app`

GET /events

List all events  
Sample Response: `{ "events": [{ _id, title, type, tags, date, thumbnailUrl, ... }] }`

GET /events/search?type=Online&q=react

Search/filter events  
Sample Response: `{ "events": [filtered results] }`

GET /events/:id

Single event details  
Sample Response: `{ "event": { title, description, sessions, speakers, venue, price, ... } }`

## Contact

For bugs or feature requests: rajeshkumarrour40@gmail.com 
