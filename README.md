# STGS – Scientific Travel Grant System

A comprehensive web application for managing academic travel grant applications and reimbursement requests at universities.

## 🎯 Features

- **User Authentication** - Secure login with role-based access control
- **Multi-User Roles** - Support for Applicants, Reviewers, Finance Managers, and Administrators
- **Grant Applications** - Submit travel grant applications with supporting documents
- **Application Tracking** - Real-time status updates with multi-step approval workflow
- **Reimbursement Management** - Submit expense claims and track reimbursement status
- **Settlement Calculation** - Automatic calculation of differences between advance payments and actual expenses
- **Responsive Design** - Mobile-friendly interface suitable for all device sizes
- **Professional UI** - Clean, modern university administration dashboard

## 🚀 Getting Started

### Prerequisites

- Node.js 16.0 or higher
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/moonnyxx/BlueDot.git
cd BlueDot

# Checkout the feature branch
git checkout feat/stgs-mvp

# Install dependencies
npm install

# Start development server
npm run dev
```

The application will open at `http://localhost:5173`

## 🔐 Demo Credentials

Login with any of these test accounts (password: `password`):

| Email | Name | Role |
|-------|------|------|
| john@university.edu | John Smith | Applicant |
| sarah@university.edu | Dr. Sarah Johnson | Reviewer |
| alice@university.edu | Alice Williams | Finance Manager |
| michael@university.edu | Michael Chen | Administrator |

## 📋 User Workflows

### 👤 Applicant
- Submit travel grant applications
- Upload supporting documents
- Track application status
- Submit reimbursement requests
- Monitor payment status

### 👨‍⚖️ Reviewer
- Review pending applications
- Approve or reject with comments
- Track approval workflow

### 💼 Finance Manager
- Review reimbursement requests
- Validate expense claims
- Process payments

### ⚙️ Administrator
- Manage system users
- Configure settings
- View audit logs

## 🏗️ Architecture

**Frontend Stack:**
- React 18 + TypeScript
- React Router v6
- Zustand for state management
- Tailwind CSS for styling
- Vite for bundling

**Key Features:**
- Multi-step approval workflow
- Real-time status tracking
- Document management
- Settlement calculations
- Role-based access control

## 📦 Project Structure

```
src/
├── components/
├── pages/
├── store.ts
├── types.ts
├── App.tsx
└── main.tsx
```

## ✨ Implemented Pages

✅ Login Page
✅ Applicant Dashboard
✅ New Application
✅ Applications List
✅ Application Details
✅ Reimbursement Request
✅ Reimbursement Tracking

## 🔒 Security

- Role-based access control
- Protected routes
- Form validation
- Data isolation per user

## 📱 Responsive Design

- Mobile-friendly interface
- Collapsible sidebar
- Adaptive layouts
- Touch-optimized

---

**Built for academic institutions to streamline travel grant management** ✈️
