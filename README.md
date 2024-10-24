# LeadManagementApp - HSR Motors Lead Management System

## Overview
Lead Management Web-Application is a modern web application designed for HSR Motors to streamline their lead management process. The system helps sales teams and business managers collaborate effectively while managing and analyzing leads from various sources including Facebook, Twitter, Google, and offline events.

## Key Features
- Real-time lead tracking and management
- Collaborative workspace for sales team
- Advanced analytics dashboard for business managers
- Lead status tracking and qualification
- Automated lead assignment and follow-up system

## Screens
1. **Lead Listing**: Comprehensive view of all leads with filtering and sorting capabilities
2. **Lead Details**: Detailed information about individual leads with communication history
3. **Lead Management**: Tools for updating lead status and assigning team members
4. **Dashboard**: Analytics and performance metrics visualization

## Tech Stack
- Frontend: React.js with TypeScript
- UI Framework: Tailwind CSS
- State Management: Redux Toolkit
- Charts: Recharts
- Forms: React Hook Form
- API Client: Axios
- Testing: Jest & React Testing Library

## Installation
```bash
# Clone the repository
git clone https://github.com/mrigankraj/leadsync-pro.git

# Navigate to project directory
cd leadsync-pro

# Install dependencies
npm install

# Start development server
npm run dev
```

## Environment Setup
Create a `.env` file in the root directory with the following variables:
```
VITE_API_BASE_URL=your_api_url
VITE_APP_ENV=development
```

## Scripts
- `npm run dev`: Start development server
- `npm run build`: Build production bundle
- `npm run test`: Run tests
- `npm run lint`: Run ESLint
- `npm run format`: Format code with Prettier

## Project Structure
```
leadsync-pro/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── store/
│   ├── types/
│   ├── utils/
│   └── App.tsx
├── public/
├── tests/
└── package.json
```

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
MIT License
