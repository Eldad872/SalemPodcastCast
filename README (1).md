 Salem International Christian Center Podcast App

A modern web application for Salem International Christian Center to share sermons, live stream services, and connect with their congregation.

## Features

### For Listeners
- **Sermon Library**: Browse, search, and filter through sermon recordings by topic, preacher, or date
- **Live Streaming**: Watch live church services with real-time streaming
- **Favorites**: Save sermons to a personal favorites list for easy access
- **Downloads**: Download sermons for offline listening
- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop devices

### For Administrators
- **Sermon Management**: Upload, edit, and manage sermon recordings
- **Live Event Control**: Schedule and manage live streaming events
- **Customization**: Update church branding with custom logo and colors
- **Analytics**: Track sermon popularity and download statistics

## Technical Implementation

This application is built with a modern tech stack:

- **Frontend**: React with TypeScript, TailwindCSS
- **UI Components**: shadcn/ui component system
- **State Management**: React Query for server state
- **Routing**: Wouter for lightweight routing
- **Storage**: Client-side storage for preferences, in-memory storage for server-side data

## Getting Started

### Installation

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm run dev
   ```

### Building for Production

```
npm run build
```

## Usage Guide

### Uploading Sermons

1. Navigate to the Admin dashboard
2. Select the "Sermons" tab
3. Click "Upload Sermon"
4. Fill in the sermon details (title, preacher, date, etc.)
5. Upload the audio file and optional thumbnail
6. Click "Upload" to add the sermon to the library

### Creating Live Events

1. Navigate to the Admin dashboard
2. Select the "Live Events" tab
3. Click "Create Live Event"
4. Fill in the event details (title, description, scheduled time, etc.)
5. Add a streaming URL when the event is ready to go live
6. Toggle the "Live" status when the event begins streaming

### Customizing Church Branding

1. Navigate to the Admin dashboard
2. Select the "Customization" tab
3. Click "Customize Church Logo"
4. Upload your church logo (recommended size: 200x200px)
5. Preview the changes and save them

## Project Structure

- `/client`: Frontend React application
  - `/src`: Source code
    - `/assets`: Images and icons
    - `/components`: Reusable UI components
    - `/hooks`: Custom React hooks
    - `/lib`: Utility functions and services
    - `/pages`: Page components for different routes
- `/server`: Backend Express server
  - `/routes.ts`: API endpoints
  - `/storage.ts`: Data storage implementation
- `/shared`: Shared code between client and server
  - `/schema.ts`: Data schemas and types

## License

This project is proprietary software for Salem International Christian Center.

## Support

For support or feature requests, please contact the development team.