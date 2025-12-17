---
title: "Events & Venues Guide"
description: "Comprehensive guide to managing events, venues, and logistics in Compass"
---

# Compass Calendar User Guide

Welcome to the Compass Calendar module. This guide provides a comprehensive overview of how to manage global events, venues, and logistics within the application.

<Note>
Access to manage events and venues is restricted to authorized users. If you do not see certain buttons (like "Add Event"), you may have view-only access.
</Note>

## 1. Calendar Overview
The Calendar is your central hub for tracking high-profile events and logistical planning.

<Frame>
  <img src="https://i.ibb.co/LztmbDhk/cal.png" alt="Calendar Overview - Shows the main calendar interface with month view, navigation controls, and filter options" />
</Frame>

- **Views**: Toggle between **Month**, **Week**, **Day**, and **Year** views using the buttons in the top right.
- **Navigation**: Use the arrow keys or "Today" button to navigate through time.
- **Filtering**: Use the filter bar to show events only for specific venues.
- **Tabs**: Switch between the **Calendar** view (timeline) and **Venues** list (database of locations).

---

## 2. Managing Events

### Adding an Event
1. Click the **Add Event** button in the top right or click on any date cell in the calendar.

<Frame>
  <img src="https://i.ibb.co/M5CP3Fb5/image.png" alt="Add Event Form - Shows the event creation form with fields for name, dates, description, and image URL" />
</Frame>

2. **Event Details**:
   - **Name**: Enter the official event name (e.g., "Monaco Grand Prix").
   - **Dates**: Select the detailed Start and End dates/times.
   - **Description**: Add internal notes or public descriptions.
   - **Image URL**: Provide a link to a high-quality cover image for the event.
3. **Link Venues**: Select one or more existing venues to associate them with this event.
4. Click **Save Event**.

### Viewing Event Details
Clicking on an event card opens the **Event Details Sheet**, a rich dashboard showing:

<Frame>
  <img src="https://i.ibb.co/1GC2YfyF/image.png" alt="Event Details Sheet - Shows the event dashboard with hero image, countdown, and venue information" />
</Frame>

- **Hero Image**: A visual header with the event's vibe.
- **Countdown & Dates**: Clear timing indicators.
- **Venues Map**: An interactive map showing all linked venues.
- **Logistics**: Transport rates and airport connections (see below).

---

## 3. Venues & Locations
Venues are the physical locations where events take place (e.g., "Monaco Circuit", "Convention Center").

### Adding a Venue
1. Navigate to the **Venues** tab or click **Add Venue**.

<Frame>
  <img src="https://i.ibb.co/B5s4hj0L/image.png" alt="Add Venue Form - Shows the venue creation form with smart search and map integration" />
</Frame>

2. **Smart Search**: Start typing in the location search bar. The system uses **Google Maps Integration** to find the exact address.
3. **Automatic Details**: Selecting a location automatically fills the address and coordinates.
4. **Dates**: Specify when this venue is active for the event.

### Smart Airport Discovery
<Tip>
The system automatically analyzes the venue's location to find **Nearby Airports**.
</Tip>

- When you add a venue, compass automatically scans for airports within a relevant radius.
- These airports are listed with their distance (miles/km) and plotted on the map.
- You can hover over airport markers to see their names and details.

---

## 4. Route Visualization & Logistics
The Event Details Sheet provides powerful visualization tools for planning travel.

### Interactive Map

<Frame>
  <img src="https://i.ibb.co/MDW5ZMcL/image.png" alt="Interactive Venue Map - Shows the venue location with nearby airports and route visualization" />
</Frame>

- The map automatically centers on the event's venues.
- **Airport Connections**: The system visually demonstrates the route from nearby airports to the venue.
- **Live Route Animation**: An animated path flows from the active airport to the venue, helping you visualize the journey.
- **Distance & Time**: The map displays the driving distance and estimated travel time for the selected route.

### Automatic Cycling
If a venue has multiple nearby airports, the view will automatically cycle through them every few seconds, giving you a passive overview of all logistical options without needing to click.

---

## 5. Rate Management
Compass allows you to manage and display transport rates directly within the event context.

### Viewing Rates
On the Event Details Sheet, you will see a **Rates Card** that cycles between:
- **Airport Transfers**: One-way pricing from specific airports.
- **Hourly Charters**: Hourly rates for disposal services.

The card displays vehicle images, prices, and important notes (like "Min. 4 hours").

### Managing Rates
(Authorized Users Only)

<Frame>
  <img src="https://i.ibb.co/chNLJwWn/image.png" alt="Rate Management - Shows the rate editing interface with service types and pricing options" />
</Frame>
<Frame>
  <img src="https://i.ibb.co/GfM4xQtv/image.png" alt="Rate Management - Shows the rate editing interface with service types and pricing options" />
</Frame>

1. Click the **Edit (Pencil)** icon on the Rates Card.
2. **Add New Rate**:
   - **Service Type**: Choose "Airport Transfer" or "Hourly Charter".
   - **Vehicle**: Select from the fleet (Sedan, SUV, Sprinter, Bus, etc.).
   - **Price**: Set the cost.
   - **Airport**: (For transfers) Search and link a specific airport.
   - **Policies**: Add cancellation terms or minimum hour requirements.
3. **Save**: The new rate immediately appears in the cycle.

---

## 6. Integrations
The Compass Calendar leverages several powerful integrations to streamline your workflow:

- **Google Maps & Places**: 
  - Powers the "Smart Search" for venues.
  - Key to the "Smart Airport Discovery" feature.
  - Generates the accurate "Route Visualizations" and driving estimates.
  
- **Gmail & Google Calendar** (Backend):
  - Seamless authentication allows for potential syncing features (check your settings for active sync options).
