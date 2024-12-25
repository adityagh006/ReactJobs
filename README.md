# ReactJobs
A modern job board application built with React, focusing on React developer positions. The application allows users to browse, add, edit, and manage job listings with a clean and intuitive interface.

### Features
- Browse job listings
- View detailed job information
- Add new job listings
- Edit existing job listings
- Delete job listings
- Responsive design with Tailwind CSS
- Client-side routing with React Router


### Technologies Used
- React
- React Router v6
- Tailwind CSS
- Vite
- JSON Server (for mock API)


### Installation

1. Clone the repository
bash
```
git clone https://github.com/yourusername/reactjobs.git
cd reactjobs
```

2. Install dependencies
bash
```
npm install
```

3. Start the development server
bash
```
npm run dev
```

4. Start the JSON server (in a separate terminal)
bash
```
json-server --watch src/data/jobs.json --port 3000
```

5. Open your browser and visit http://localhost:5173


### Project Structure
```
Copyreactjobs/
├── src/
│   ├── layouts/
│   │   └── MainLayout.jsx
│   ├── pages/
│   │   ├── HomePage.jsx
│   │   ├── JobsPage.jsx
│   │   ├── JobPage.jsx
│   │   ├── AddJobPage.jsx
│   │   ├── EditJobPage.jsx
│   │   └── NotFoundPage.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── public/
├── index.html
└── package.json
```


### API Endpoints
- GET /api/jobs - Get all jobs
- GET /api/jobs/:id - Get single job
- POST /api/jobs - Add new job
- PUT /api/jobs/:id - Update job
- DELETE /api/jobs/:id - Delete job


## Features in Detail

### Job Listing
  - View all available job positions
  - Filter and search functionality
  - Detailed view for each job listing

Job Management

Add new job listings with company details
Edit existing job information
Remove job listings
View company information

Contributing

Fork the repository
Create your feature branch

bashCopygit checkout -b feature/YourFeature

Commit your changes

bashCopygit commit -m 'Add some feature'

Push to the branch

bashCopygit push origin feature/YourFeature

Create a new Pull Request

License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

React Router for the routing solution
Tailwind CSS for the styling framework
Vite for the build tool
JSON Server for the mock backend
