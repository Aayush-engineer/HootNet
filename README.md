# Skillset - A Community Platform for Teachers and Students

**Skillset** is a feature-rich online platform designed to connect teachers, tutors, and students. This platform provides tools for creating, managing, and sharing live classes, courses, and educational content. Teachers can offer personalized tutoring, while students can access classes, track progress, and engage with learning materials in an interactive way.

### Features
- **Live Classes**: Teachers can host live classes, workshops, and sessions for students in real-time with video streaming and interactive tools.
- **Course Creation**: Teachers can create and organize full courses with modules, assignments, and quizzes.
- **Interactive Learning**: Real-time quizzes, whiteboards, student discussions, and live feedback help increase engagement.
- **Monetization**: Teachers can monetize their content through subscriptions, pay-per-class, and tip features.
- **Student Dashboard**: Personalized learning path, progress tracking, and access to all enrolled classes.
- **Payment Integration**: Integrated payment system via **Stripe** for seamless class bookings, course purchases, and teacher payouts.
- **Certification**: Teachers can offer certification upon course completion.
- **AI-Powered Recommendations**: AI-powered content recommendations based on student preferences, interests, and progress.
- **Freelance Marketplace**: Teachers can list their services and offer one-on-one tutoring or specialized classes.

### Tech Stack
- **Frontend**: Next.js 14, React, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: Prisma ORM, Neon (PostgreSQL), MySQL
- **Authentication**: Clerk (for secure user authentication and management)
- **Payment Gateway**: Stripe
- **File Storage**: Cloudinary AI (for media uploads, course materials, and AI-generated content)
- **AI**: Custom AI models for content recommendations and personalized learning
- **Hosting/Deployment**: Vercel

### Why Choose Skillset?
- **Tailored for Education**: Unlike general video conferencing tools like Zoom, Skillset is built specifically for educators and students, with features focused on teaching, learning, and community-building.
- **Interactive Tools**: Engaging tools like live quizzes, whiteboards, and real-time feedback keep students involved in the learning process.
- **Affordable & Scalable**: Teachers can monetize their content easily and scale their teaching business. Students can find personalized learning experiences at competitive prices.
- **AI Features**: Skillset leverages AI to recommend relevant courses, tutoring, and content for students, enhancing the learning experience.
- **Focus on Small Classes and Tutoring**: Unlike massive platforms, Skillset allows teachers to offer small, focused classes and one-on-one tutoring.

---

## Setup Instructions

### Prerequisites

Make sure you have the following installed on your system:
- **Node.js** (version 16 or above)
- **Yarn** or **npm**
- **PostgreSQL** or **MySQL** (depending on the database choice)
- **Cloudinary account** (for image/video storage)
- **Stripe account** (for payment integration)

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/skillset.git
cd skillset
