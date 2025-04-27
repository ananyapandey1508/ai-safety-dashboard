# AI Safety Incident Dashboard

This project is an interactive dashboard for tracking and reporting AI safety incidents. It allows users to view, filter, sort, and add new incidents.

## Features

- Display a list of AI safety incidents with Title, Severity, and Reported Date
- Filter incidents by Severity (All, Low, Medium, High)
- Sort incidents by Reported Date (Newest First, Oldest First)
- Toggle incident details with "View Details" button
- Add new incidents with a form that includes validation
- Responsive design that works on mobile and desktop

## Technology Stack

- **Language/Framework**: TypeScript with Next.js (App Router)
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **State Management**: React hooks (useState)

## Getting Started

### Prerequisites

- Node.js 18.x or later
- npm or yarn

### Installation

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/yourusername/ai-safety-dashboard.git
   cd ai-safety-dashboard
   \`\`\`

2. Install dependencies:
   \`\`\`bash
   npm install
   # or
   yarn install
   \`\`\`

3. Run the development server:
   \`\`\`bash
   npm run dev
   # or
   yarn dev
   \`\`\`

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Design Decisions

- **Component Structure**: The dashboard is broken down into smaller, reusable components for better maintainability.
- **State Management**: All state is managed locally using React's useState hook, as specified in the requirements.
- **Form Validation**: Basic validation ensures that required fields are filled before submitting.
- **Responsive Design**: The layout adjusts for different screen sizes using Tailwind's responsive utilities.
- **Accessibility**: The application includes proper labeling and semantic HTML for better accessibility.

## Data Persistence

As per the requirements, all data is handled locally within the frontend application state (in memory). Any data added by the user only persists for the current session.
