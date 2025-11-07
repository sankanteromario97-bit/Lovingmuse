Loving Muse; Lobi - Fantasy Roleplay Chat Platform
A comprehensive web-based fantasy roleplay chat application with separate interfaces for clients, moderators, and administrators.

🎨 Design Features
Color Scheme: Light blue and pink gradient theme throughout
Responsive Design: Mobile-first approach with elegant UI
Dark Mode Support: Full dark mode implementation
Smooth Animations: Floating elements and gradient transitions
🚀 Key Features
For Clients
✅ User registration and login system
✅ Browse characters by genre (Love, Romance, Sexual Preferences)
✅ Detailed character profiles with 20+ attributes:
Name, Age, Relationship Status, City, Birthday
Hobbies, Children, Pets, Gender, Health
Physical attributes: Eye color, Hair color, Height, Weight
Lifestyle: Piercings, Tattoos, Smoker, Drinker
Additional custom details
✅ Credit-based payment system (1 credit per message)
✅ Multiple payment options: Credit Card, PayPal, Bitcoin, USDT
✅ Real-time chat interface
✅ Chat history and credit tracking
For Moderators
✅ Moderator login and dashboard
✅ Create and manage multiple character profiles
✅ Upload character photos
✅ Manage active chat sessions
✅ Real-time chat interface with clients
✅ Sound notifications when receiving new messages from clients
✅ Earnings tracking and statistics
✅ Character performance metrics
For Administrators
✅ Admin login panel
✅ Create moderator accounts
✅ View and manage all moderators
✅ Edit client profiles
✅ View all registered clients
✅ System overview and statistics
🛠️ Technical Stack
Framework: Next.js 15.2 (Page Router)
Language: TypeScript
Styling: Tailwind CSS v3
UI Components: Shadcn/UI
Icons: Lucide React
Storage: LocalStorage (for demo - easily upgradable to Supabase/Firebase)
Notifications: Custom Web Audio API sound alerts
📁 Project Structure
src/
├── components/          # Reusable UI components
│   └── ui/             # Shadcn/UI components
├── contexts/           # Theme and global state
├── lib/                # Utility functions
│   ├── storage.ts      # LocalStorage management
│   └── notificationSound.ts  # Sound notification system
├── pages/              # Next.js pages
│   ├── index.tsx       # Landing page
│   ├── client/         # Client interface
│   │   ├── login.tsx
│   │   ├── register.tsx
│   │   ├── dashboard.tsx
│   │   └── chat/[characterId].tsx
│   ├── moderator/      # Moderator interface
│   │   ├── login.tsx
│   │   └── dashboard.tsx
│   └── admin/          # Admin interface
│       ├── login.tsx
│       └── dashboard.tsx
├── styles/             # Global styles
└── types/              # TypeScript type definitions
🔐 Demo Accounts
Admin Account
Email: admin@lovingmuse.com
Password: Romariotv97
Test Moderator (auto-created)
Email: moderator@example.com
Password: mod123
Test Client (auto-created)
Email: client@example.com
Password: client123
Starting Credits: 100
🎯 How to Use
As Admin:
Login at /admin/login
Create moderator accounts from the dashboard
View and manage all users
Edit client profiles as needed
As Moderator:
Login at /moderator/login
Create character profiles with detailed attributes
Upload character photos
Monitor active chat sessions
Respond to client messages (sound alerts notify you of new messages)
Track your earnings and performance
As Client:
Register at /client/register
Purchase credits (payment integration ready)
Browse available characters
Start conversations (1 credit per message)
Enjoy private, secure conversations
🔊 Sound Notifications
Moderators receive automatic sound notifications when:

A client sends a new message
Notifications play every 3 seconds when unread messages are present
Uses Web Audio API for browser-native sound generation
💳 Payment Integration Ready
The platform is prepared for payment integration with:

Credit Cards (Stripe ready)
PayPal (integration ready)
Bitcoin (crypto wallet ready)
USDT/Tether (crypto wallet ready)
🔒 Privacy & Safety Features
18+ Age Verification: Clear disclaimers on all pages
Fictional Characters: All characters are clearly marked as fictional
Private Conversations: Secure, confidential chat system
Consent-Based: All interactions are voluntary and consensual
📱 Responsive Design
Desktop-optimized layouts
Mobile-friendly interfaces
Tablet support
Touch-friendly controls
🎨 Customization
The color scheme can be easily customized in:

src/styles/globals.css - CSS variables for colors
tailwind.config.ts - Tailwind theme configuration
Current color palette:

Primary: Light Blue (#60A5FA / #93C5FD)
Secondary: Pink (#F9A8D4 / #F472B6)
Accent: Purple (#C084FC / #A78BFA)
🚀 Getting Started
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
📝 Future Enhancements
Backend integration (Supabase/Firebase)
Real payment processing
Advanced analytics dashboard
Video/voice chat capabilities
Advanced character AI responses
Mobile app versions
⚖️ Legal Compliance
Adults Only: 18+ age verification required
Clear Disclaimers: All content marked as fictional
Privacy Policy: User data protection measures
Terms of Service: Clear usage guidelines
🤝 Support
For technical issues or questions, contact Softgen Support through the Softgen interface.

Built with ❤️ using Softgen AI

All characters are fictional. This is an entertainment platform for adults only.
