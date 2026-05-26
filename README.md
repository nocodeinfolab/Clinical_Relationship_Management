# Referral Nexus – Clinical Relationship Management System

## Overview

Referral Nexus is a modern oncology-focused Clinical Relationship Management (CRM) platform designed for hospitals and cancer treatment centers to manage:

- Referring doctors
- Patient referrals
- Clinical care pipeline progression
- Liaison officer performance
- Communication tracking

The platform provides a centralized dashboard for managing referral networks and monitoring patient movement through different treatment stages.

Built with:
- HTML5
- CSS3
- Vanilla JavaScript
- Supabase

---

# Features

## Referral Network Management

The system allows hospitals to:

- Onboard referring doctors
- Assign physician liaisons
- Manage referral relationships
- Track referral performance
- Maintain doctor directories

---

# Patient Referral Management

Users can:
- Register referred patients
- Link patients to referring doctors
- Assign referral priority
- Add clinical notes
- Track referral history

---

# Clinical Care Pipeline

The application includes a complete oncology treatment workflow system.

Supported treatment stages include:

- Preliminary Consultation
- Preliminary Tests
- Chemotherapy
- CT Simulation
- Radiotherapy
- Brachytherapy
- Surgery
- Palliative Care

Staff can:
- Advance patients through stages
- Record completed stages
- Trigger doctor notifications
- Monitor stage progression visually

---

# Communication Tracking

The platform logs outbound communications sent to referring physicians.

Supported communication channels:
- Email
- WhatsApp
- SMS

Communication logs include:
- Doctor name
- Patient name
- Stage update
- Delivery channel
- Status
- Timestamp

---

# Liaison Officer Management

The system includes a dedicated liaison performance module for:

- Recording field visits
- Tracking doctor onboarding
- Managing corporate outreach
- Monitoring lead generation
- Measuring deal conversion

---

# Dashboard Analytics

The dashboard provides real-time KPIs including:

- Total referrals
- Active doctors
- Patients enrolled
- Messages sent
- Stage distribution
- Top referring doctors
- Liaison performance rankings

---

# Technologies Used

## Frontend
- HTML5
- CSS3
- Vanilla JavaScript

## Backend
- Supabase

## Database
- PostgreSQL (via Supabase)

## Authentication
- Supabase Auth

## External Libraries
- Supabase JavaScript SDK
- Google Fonts

---

# Project Structure

```plaintext
project/
│
├── dashboard.html
│
├── Embedded CSS
│   ├── Dashboard Layout
│   ├── Responsive Design
│   ├── Tables
│   ├── Cards
│   ├── Analytics Components
│   ├── Toast Notifications
│   └── Pipeline Visualization
│
└── Embedded JavaScript
    ├── Authentication
    ├── Dashboard Metrics
    ├── Referral Management
    ├── Doctor Management
    ├── Communication Logs
    ├── Liaison Tracking
    ├── Supabase Integration
    └── Real-Time UI Updates
```

---

# Core Modules

## Dashboard

Provides:
- Referral analytics
- Doctor rankings
- Liaison rankings
- Stage statistics
- KPI summaries

---

## Referring Doctors Module

Features:
- Doctor onboarding
- Doctor directory
- Liaison assignment
- Search and filtering

---

## Patients & Referrals Module

Features:
- Patient registration
- Referral creation
- Priority assignment
- Referral history

---

## Care Pipeline Module

Features:
- Stage advancement
- Pipeline visualization
- Stage history tracking
- Automated notifications

---

## Communications Module

Features:
- Communication logs
- Delivery tracking
- Channel management
- Search and filtering

---

## Liaison Officers Module

Features:
- Field activity tracking
- Corporate outreach monitoring
- Lead generation tracking
- Performance leaderboard

---

# Supabase Integration

The application integrates directly with Supabase for:

- Authentication
- Database operations
- Session management
- Real-time data handling

---

# Database Tables

The platform uses multiple relational tables including:

```plaintext
- referring_doctors
- physician_liaisons
- patients
- referral_cases
- referral_stage_history
- communication_logs
```

---

# Authentication Flow

## Step 1
User logs in through Supabase Auth.

## Step 2
Session is validated.

## Step 3
Unauthorized users are redirected to login.

## Step 4
Authorized users gain access to the dashboard.

---

# Dashboard Analytics

The system dynamically calculates:

- Referral counts
- Doctor performance
- Liaison performance
- Stage completion distribution
- Communication activity

---

# Responsive Design

The interface is optimized for:
- Desktop systems
- Tablets
- Mobile devices

Using:
- CSS Grid
- Flexbox
- Media queries
- Adaptive layouts

---

# UI Features

## Real-Time Clock
Displays live operational time.

---

## Interactive Dashboards
Provides live KPI cards and rankings.

---

## Pipeline Visualization
Displays patient treatment progression visually.

---

## Toast Notifications
Provides:
- Success messages
- Error messages
- Real-time feedback

---

# Communication Workflow

## Stage Completion Process

### Step 1
Select referral case.

### Step 2
Choose completed stage.

### Step 3
Select notification channels.

### Step 4
System logs communication activity.

### Step 5
Doctor receives notification.

---

# Security Features

Current implementation includes:
- Supabase authentication
- Session validation
- Access control
- Secure database queries

---

# Recommended Improvements

Potential future enhancements include:

- Role-based permissions
- Multi-hospital tenancy
- Referral analytics charts
- Automated email templates
- WhatsApp API integration
- SMS gateway integration
- File upload support
- EMR integration
- Audit logs
- Advanced reporting
- AI-assisted referral prediction

---

# Healthcare Use Case

This platform is especially suitable for:

- Oncology centers
- Specialist hospitals
- Referral hospitals
- Multi-branch healthcare organizations
- Clinical outreach programs

---

# Deployment

This application can be deployed on:
- Vercel
- Netlify
- Render
- Cloudflare Pages

---

# Running Locally

## Clone Repository

```bash
git clone https://github.com/yourusername/referral-nexus.git
```

---

## Open Project

Open:

```plaintext
dashboard.html
```

in your browser.

Or run using a local server:

```bash
python -m http.server
```

---

# Supabase Configuration

Before deployment, replace:

```javascript
const db = createClient(
    "YOUR_SUPABASE_URL",
    "YOUR_SUPABASE_ANON_KEY"
);
```

with your own Supabase project credentials.

---

# Author

Chikezie Abia  
Healthcare Software Developer  
Medical Laboratory Scientist  
Nigeria

---

# License

This project is licensed under the MIT License.
