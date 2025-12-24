# GHS Carnival – Official Sports Fest Website

## Overview
GHS Carnival is the annual college sports fest featuring multiple sports competitions between hostel blocks. This website serves as the central digital platform for live scores, schedules, team information, and official updates. Scores are updated manually through a secure admin panel by designated sport coordinators.

---

## Objectives
- Display accurate live scores for all sports
- Allow manual score updates by authorized admins
- Centralize all fest-related information
- Provide a mobile-first, easy-to-use interface
- Support simultaneous updates for multiple sports

---

## Website Structure

### Public Website
- Landing Page
- Live Scores
  - Box Cricket
  - Football / Futsal
  - Basketball
  - Volleyball
  - Table Tennis
  - Other Sports
- Teams & Organising Committee
- Hostel Blocks & Captains
- About Us
- Guidelines / Rulebook

### Admin System (Restricted)
- Admin Login
- Sport-wise Score Update Panels
- Match & Schedule Management
- Announcements & Links Management
- Admin Activity Logs

---

## 1. Landing Page
**Purpose:** Entry point and overview of the fest

**Contents:**
- Fest branding, dates, and tagline
- Navigation menu
- Live match highlights
- Announcements
- Sports quick-access icons
- Footer with social links and contact info

---

## 2. Live Scores (Public)

### Purpose
Display real-time match information (read-only).

### Sports Selector
- Horizontal scrollable sports list
- Active sport highlighted

### Sport Live Score View
**Now Playing Section:**
- Teams playing
- Live indicator
- Score details (sport-specific)
- Match status

**Up Next Section:**
- Upcoming matches
- Date and time
- Venue (optional)

**Quick Links:**
- Official Instagram page
- Guidelines / Rulebook
- Cultural events updates

### Sport-Specific Score Data
- Box Cricket: Runs, wickets, balls, innings
- Football/Futsal: Goals, time, half
- Basketball: Score, quarter
- Volleyball: Sets, points
- Table Tennis: Sets, points

---

## 3. Teams & Organising Committee
**Purpose:** Display the people behind the fest

**Contents:**
- Core committee members
- Sub-committees
- Names, roles, photos, contact (optional)

---

## 4. Hostel Blocks & Captains
**Purpose:** Show participating hostel blocks and leadership

**Contents:**
- Block name
- Block captain name and photo
- Sports participation details
- Optional vice-captain information

---

## 5. About Us
**Purpose:** Describe the fest and its vision

**Contents:**
- History of GHS Carnival
- Vision and mission
- Values and sportsmanship
- Participation scale

---

## 6. Guidelines / Rulebook
**Purpose:** Provide official rules and regulations

**Contents:**
- General rules
- Sport-specific rules
- Match formats and scoring
- Code of conduct
- Disqualification policies
- Downloadable rulebook

---

## 7. Admin Panel

### Purpose
Allow authorized individuals to manually update scores and manage match data.

### Roles
- Super Admin: Full access to all sports, users, and content
- Sport Admin: Access limited to assigned sport

### Admin Login
- Secure authentication
- Role-based access control

### Admin Dashboard
- Assigned sport overview
- Ongoing and upcoming matches
- Match control actions

### Sport-wise Score Update
**Inputs (varies by sport):**
- Team names
- Score fields
- Time / balls / sets
- Match status (Live / Completed / Upcoming)

**Controls:**
- Increment/decrement score
- Manual correction fields
- Save/update actions
- Start/end match controls

### Live Sync
- Updates reflected instantly on public pages
- No public write access

### Safety & Validation
- Confirmation prompts
- Input validation
- Update logs with timestamps
- Rollback for recent updates

---

## 8. Announcements & Links Management
- Update social media links
- Update guideline links
- Push announcements to landing page

---

## Technical Considerations

### Frontend
- Mobile-first responsive UI
- Read-only public views
- Admin-only editable views

### Backend
- Authentication and authorization
- Real-time or near real-time data updates

### Database Entities
- Users (Admins)
- Sports
- Matches
- Scores
- Announcements

---

## Security
- Role-based permissions
- Secure admin authentication
- No public data modification
- Admin activity logging

---

## Future Enhancements
- Player statistics
- Match commentary
- Push notifications
- Progressive Web App support
- Admin mobile-optimized interface
