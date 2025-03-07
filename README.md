# Travel Deal Finder 🌍✈️

A modern web application that helps travelers find and compare the best flight deals by analyzing cash prices versus points redemptions, and discovering alternative purchase options.

![Travel Deal Finder Banner](https://images.unsplash.com/photo-1436491865332-7a61a109cc05?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1200&q=80)

## ✨ Features

- **Cash vs. Points Comparison**: Easily compare if using cash or points offers better value
- **Alternative Purchase Options**: Discover if booking through partner airlines or other portals saves money
- **User-Friendly Interface**: Clean, intuitive design built with React and Tailwind CSS
- **Real-Time Data**: Integration with flight pricing APIs for up-to-date information
- **Personalized Recommendations**: Save your preferences and receive tailored deal alerts
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- API keys for flight data services (instructions below)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AIspowers/travel-deal-finder.git
   cd travel-deal-finder
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory with the following variables:
   ```
   NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_firebase_app_id
   
   OPENAI_API_KEY=your_openai_api_key
   ANTHROPIC_API_KEY=your_anthropic_api_key
   REPLICATE_API_KEY=your_replicate_api_key
   DEEPGRAM_API_KEY=your_deepgram_api_key
   
   # Flight data API keys (as needed)
   AMADEUS_API_KEY=your_amadeus_api_key
   AMADEUS_API_SECRET=your_amadeus_api_secret
   ```

4. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 🏗️ Project Structure

```
/src
  /app                 # Next.js App Router pages and layouts
    /api               # API routes for backend functionality
    /components        # React components
    page.tsx           # Home page
    layout.tsx         # Root layout
  /lib                 # Utility functions, hooks, and contexts
    /contexts          # React contexts (Auth, Deepgram)
    /firebase          # Firebase configuration and utilities
    /hooks             # Custom React hooks
```

## 🔧 Technologies Used

- **Frontend**:
  - Next.js 14 (App Router)
  - React
  - TypeScript
  - Tailwind CSS
  - Vercel AI SDK

- **Backend & APIs**:
  - Firebase (Authentication, Database, Storage)
  - OpenAI API
  - Anthropic API
  - Replicate API
  - Deepgram API
  - Flight data APIs (Amadeus, etc.)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- [Next.js](https://nextjs.org/)
- [Vercel](https://vercel.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Firebase](https://firebase.google.com/)
- [Unsplash](https://unsplash.com/) for the banner image

---

Built with ❤️ by [Your Name/Team]
