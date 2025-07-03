# ChatSnap

ChatSnap is a modern social media and messaging platform that combines the best features of popular social networks and messaging apps. Built with Next.js, TypeScript, and Tailwind CSS, it offers a seamless experience for connecting, communicating, and sharing life moments.

## Features

- **Authentication**
  - Email/Phone registration and login
  - Secure session management
  - Protected routes

- **Profile Management**
  - Customizable user profiles
  - Profile picture upload
  - Bio and personal information

- **Social Feed**
  - Photo and video sharing
  - Stories feature (24-hour temporary content)
  - Like and comment on posts
  - Real-time updates

- **Messaging**
  - One-on-one chats
  - Group conversations
  - Media sharing in chats
  - Real-time message delivery

- **Voice & Video Calls**
  - One-on-one voice calls
  - Video calling capability
  - Call controls (mute, video toggle)

- **Channels**
  - Public broadcast channels
  - Channel subscriptions
  - Content discovery

## Tech Stack

- **Frontend**
  - Next.js 14 (App Router)
  - TypeScript
  - Tailwind CSS
  - Shadcn UI Components
  - Axios for API calls

- **Features**
  - Real-time messaging
  - File uploads
  - Voice/Video calls
  - Responsive design
  - Modern UI/UX

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/chatsnap.git
   cd chatsnap
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env.local` file in the root directory:
   ```env
   NEXT_PUBLIC_API_URL=your_api_url
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the app.

## Project Structure

```
src/
├── app/                    # Next.js app directory
│   ├── (authenticated)/    # Protected routes
│   ├── auth/              # Authentication pages
│   └── layout.tsx         # Root layout
├── components/            # Reusable components
│   ├── ui/               # UI components
│   └── layout/           # Layout components
├── lib/                  # Utilities and API
├── providers/            # Context providers
└── middleware.ts         # Auth middleware
```

## Authentication Flow

1. User registers or logs in
2. JWT token is stored in localStorage
3. Protected routes check auth status
4. Unauthorized access redirects to login

## Development Guidelines

- Follow TypeScript best practices
- Use Tailwind CSS for styling
- Implement proper error handling
- Maintain responsive design
- Write clean, documented code

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript checks

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
