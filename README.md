# 🌍 Echoes of Change

**Echoes of Change** is a Django-based web application that connects volunteers with initiatives aligned to their skills, interests, and availability. Built to support the UN Sustainable Development Goals **(SDG 3: Good Health and Well-being)** and **(SDG 10: Reduced Inequalities)**, the platform promotes meaningful community engagement through technology.

## 🎯 Key Features
- **Smart Matching Algorithm** – Matches volunteers with opportunities based on interests, skills, and availability.
- **Impact Score System** – Quantifies user contribution based on logged volunteer hours.
- **Gamified Leaderboard** – Real-time rankings to motivate and increase participation.
- **Live Global Chat** – Real-time chat for volunteers using Pusher API.
- **Chatbot Assistant** – AI-powered chatbot for instant help using OpenAI API.
- **Opportunity Map Search** – Explore local opportunities via Google Maps API.
- **Secure Donations Page** – Support causes directly using Stripe API.
- **Google Sign-In** – Streamlined authentication using Auth0.
- **Profile and Timesheet Management** – Track, log, and visualize contributions.

## 🧱 Tech Stack

**Frontend:**
- HTML, CSS, Sass
- JavaScript (Vanilla)
- Tailwind CSS, Bootstrap

**Backend:**
- Python (Django)
- Django ORM
- SQLite (planned upgrade to PostgreSQL/MySQL)

**APIs Used:**
- Google Maps API
- OpenAI API
- Stripe API
- Pusher API
- Auth0

## 🔒 Security & Compliance
- GDPR-compliant data handling
- Encrypted password storage
- Django's built-in security for CSRF, XSS, and SQL Injection

## 🚀 Deployment & CI/CD
- Dockerized application using Docker and docker-compose
- GitLab CI/CD pipelines
- Modular MVC architecture for scalability and maintainability

## 📊 Evaluation & Testing
- 32 unit tests using Django's test framework
- User acceptance testing via Google Forms
- Manual testing and peer code reviews

## 💡 Future Enhancements
- Multi-factor authentication
- NLP-based moderation for chats and reviews
- Dynamic pagination & client-side caching
- Social media sign-ins (Facebook, Twitter)
- Accessibility improvements (text-to-speech, high contrast mode)

## 👥 Team Contributions
This project was developed collaboratively using Agile methodology, rotating project managers every two weeks, and engaging in continuous user feedback and code reviews.

---

Feel free to fork, contribute, and suggest improvements via issues or pull requests!
