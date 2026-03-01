# East Asia Spring Escape - Travel Planner

An interactive travel itinerary planner for an East Asia trip covering Tokyo, Jeju Island, and Seoul.

## Features

- **Day-by-day itinerary** with timeline view, filterable by location
- **Expense tracking** per itinerary item with running totals per day, per location, and overall trip
- **Interactive maps** per day using Leaflet.js with numbered location pins and route visualization
- **Cherry blossom** falling animation for the spring theme
- **Responsive design** built with Tailwind CSS
- **Persistent expenses** saved to localStorage

## How to Use

1. Open `index.html` in any modern browser
2. Use the filter tabs to view the full itinerary or filter by city (Tokyo, Jeju, Seoul)
3. Click the **Map** button on any day card to see an interactive map with all stops plotted
4. Edit the **$** expense field next to any event to track your spending -- totals update live
5. Expenses are automatically saved to your browser's localStorage

## Tech Stack

- HTML5 + inline JavaScript (single-file app, no build step)
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Lucide Icons](https://lucide.dev/) for UI icons
- [Leaflet.js](https://leafletjs.com/) + OpenStreetMap for interactive maps
