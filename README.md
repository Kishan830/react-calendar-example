# Communication Tracking Calendar Application

A React-based calendar application designed for efficient tracking and management of business communications. This application helps maintain professional relationships by providing a centralized platform for logging interactions, planning future communications, and managing engagement schedules with various organizations.

## 🌟 Features

### Admin Module
- **Company Management**
  - Add, edit, and delete company profiles
  - Store company details including name, location, LinkedIn profile, contact information
  - Set communication periodicity for each company
  - Manage additional notes and comments

- **Communication Method Management**
  - Configure different types of communication methods
  - Set sequence and mandatory requirements
  - Default methods include: LinkedIn Post, LinkedIn Message, Email, Phone Call, Other

### User Module
- **Interactive Dashboard**
  - Grid view of companies and their communication status
  - Color-coded highlights for overdue (red) and due (yellow) communications
  - Last five communications summary
  - Next scheduled communication display

- **Communication Tracking**
  - Log new communications with notes and timestamps
  - Multi-select companies for batch updates
  - Hover tooltips for detailed information

- **Calendar View**
  - Visual representation of past and upcoming communications
  - Interactive calendar interface
  - Easy scheduling and management

### Reporting Module
- Communication frequency analysis
- Engagement effectiveness metrics
- Overdue communication trends
- Downloadable reports in PDF/CSV formats
- Real-time activity logging

## 🛠️ Technology Stack

- **Frontend**: React with TypeScript
- **State Management**: Redux Toolkit
- **Styling**: Tailwind CSS
- **Calendar**: FullCalendar
- **Charts**: Recharts
- **Routing**: React Router Dom
- **Date Handling**: date-fns
- **Icons**: Heroicons

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Git

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/communication-tracker.git
cd communication-tracker
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
REACT_APP_API_URL=your_api_url
```

4. Start the development server:
```bash
npm start
```

## 🌐 Deployment

This application is configured for deployment on Vercel:

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy to Vercel:
```bash
vercel
```

Or deploy via Vercel Dashboard:
1. Push your code to GitHub
2. Import project in Vercel Dashboard
3. Configure build settings
4. Deploy

## 📖 Usage

### Admin Setup
1. Navigate to `/admin/companies` to set up company profiles
2. Configure communication methods at `/admin/methods`
3. Set up default communication sequences

### User Operations
1. View dashboard at `/dashboard`
2. Log communications using the "Communication Performed" button
3. Check notifications for overdue and due communications
4. Use calendar view for scheduling

### Reporting
1. Access reports at `/reports`
2. Generate and download analysis
3. View real-time activity logs

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/YourFeature`
3. Commit changes: `git commit -m 'Add YourFeature'`
4. Push to branch: `git push origin feature/YourFeature`
5. Submit a pull request

## 📝 Notes

- All times are stored in UTC
- Communication schedules respect company's local timezone
- Default communication period is set to 2 weeks
- Automatic email notifications are sent for overdue communications

## ⚠️ Known Issues

- Calendar view performance may degrade with large datasets
- Some browsers may display tooltips differently
- Mobile view optimization in progress

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Contact

For questions and support, please contact:
- Email: your.email@example.com
- GitHub Issues: [Project Issues Page](https://github.com/yourusername/communication-tracker/issues)

## 🙏 Acknowledgments

- Thanks to all contributors
- Built with React and modern web technologies
- Inspired by the need for better communication tracking in professional relationships
