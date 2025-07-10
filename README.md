# 🌟 CrowdfundIt — A Full Stack Crowdfunding Platform

Welcome to **CrowdfundIt**, a modern, full-stack crowdfunding web application where users can create, explore, and contribute to campaigns that matter. Built with **Next.js (Frontend)** and **Django (Backend)**, this platform offers seamless integration, beautiful UI, and real-world functionality.

---

## 🛠️ Tech Stack

| Layer      | Technology          |
|------------|---------------------|
| Frontend   | **Next.js 15**, javasript/typescript, Tailwind CSS, Bootstrap |
| Backend    | **Django**, Django REST Framework |
| Database   | PostgreSQL / MySQL (based on backend) |
| Auth       | JWT / Session-based |
| Payments   | Stripe API (for campaign donations) |
| Styling    | Tailwind CSS + Bootstrap |
| State Mgmt | React `useState`, `useEffect` |

---

## 📁 Project Structure (Frontend)

src/
│
├── app/ # Next.js App Router pages
│ ├── page.tsx # Main Home Page
│ ├── layout.tsx # App Layout with Navbar + Footer
│ ├── about/ # About page
│ ├── login/ # Login page
│ ├── register/ # Register page
│ ├── create-campaign/ # Create new campaign page
│ └── campaigns/[id]/ # Dynamic campaign detail page
│
├── components/
│ ├── Navbar.tsx
│ ├── Footer.tsx
│ ├── HomePageContent.tsx
│ └── CampaignCard.tsx (optional)
│
├── services/
│ └── api.ts # Axios setup for backend requests
│
├── styles/
│ └── globals.css # Global styles (Tailwind + Bootstrap)

yaml
Copy
Edit

---

## 🚀 Features

- 🧭 **Dynamic Campaign Pages** (`/campaigns/[id]`)
- 📝 **Create Campaign** with form validation
- 💳 **Stripe Integration** for donations
- 🔒 **JWT Authentication** (Login/Register)
- 🌐 Responsive UI with Tailwind + Bootstrap
- 🎨 Light and Clean UI/UX
- 📦 Modular component architecture

---

## 🧑‍💻 Getting Started

### 📦 1. Clone the repository

```bash
git clone https://github.com/durgeshkumarraj/crowdfundit.git
cd crowdfundit
💻 2. Install frontend dependencies
bash
Copy
Edit
cd frontend
npm install
🔧 3. Setup Tailwind CSS (already configured)
Make sure postcss.config.js and tailwind.config.js exist.

🧪 4. Start development server
bash
Copy
Edit
npm run dev
App runs at: http://localhost:3000

⚙️ 5. Backend Setup (Django)
bash
Copy
Edit
cd backend
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
API runs at: http://localhost:8000

📸 Screenshots
You can insert screenshots here:

Home Page

Campaign Details

Create Campaign Page

Responsive Navbar

🌐 Environment Variables
You may need the following .env setup:

env
Copy
Edit
# .env.local
NEXT_PUBLIC_API_BASE_URL=http://localhost:8000/api
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_publishable_key_here
🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

📄 License
MIT

📬 Contact
🧑‍💻 Author: Durgesh Kumar

🌐 GitHub: @durgeshkumarraj
