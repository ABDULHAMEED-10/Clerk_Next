# Next Notepad App

## Overview

This project is a full-stack Next.js notepad application with AI suggestions. It uses Firebase for backend services and authentication, including JWT and OAuth.

## Features

- **AI Suggestions**: Get intelligent suggestions while taking notes.
- **JWT Authentication**: Secure your notes with JSON Web Tokens.
- **OAuth Integration**: Login using popular OAuth providers.
- **Firebase Backend**: Real-time database and authentication.

## Tech Stack

- **Frontend**: Next.js, React
- **Backend**: Firebase
- **Authentication**: JWT, OAuth
- **AI**: Integrated AI suggestion service

## Getting Started

### Prerequisites

- Node.js
- Firebase account
- OAuth provider credentials (e.g., Google, GitHub)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/next-notepad-app.git
   cd next-notepad-app
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up Firebase**:

   - Create a Firebase project.
   - Enable Firestore and Authentication.
   - Download the `firebaseConfig` and add it to your project.

4. **Configure environment variables**:
   Create a `.env.local` file and add your Firebase and OAuth credentials:

   ```env
   NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
   NEXT_PUBLIC_OAUTH_CLIENT_ID=your_oauth_client_id
   NEXT_PUBLIC_OAUTH_CLIENT_SECRET=your_oauth_client_secret
   ```

5. **Run the development server**:

   ```bash
   npm run dev
   ```

6. **Open your browser**:
   Navigate to `http://localhost:3000`.

## Usage

- **Login**: Use OAuth to log in.
- **Create Notes**: Start taking notes and get AI suggestions.
- **Secure Notes**: Your notes are securely stored with JWT authentication.

## Deployment

To deploy the app, follow the Next.js deployment documentation for your preferred platform (e.g., Vercel, Firebase Hosting).

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any questions or feedback, please contact [your-email@example.com].
