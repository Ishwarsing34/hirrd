# HIRRD - Job Portal for Software Engineers  

HIRRD is a modern job portal where recruiters can post job listings, and candidates can search, apply, and track job statuses.  

## 🚀 Live Demo  
[Click here to view the project](https://hirrd-nine-nu.vercel.app/)  


![image](https://github.com/user-attachments/assets/4dd78eb7-4cca-49b7-98b4-b9ebc7fc084f)


## 📌 Features  
- **User Authentication** (Login & Sign Up) using Clerk  
- **Job Posting** for recruiters  
- **Job Search & Filtering** for candidates  
- **Save & Apply for Jobs**  
- **Job Status Tracking** (Applied, Accepted, Rejected)  
- **Resume Buckets** – Select & attach resumes from uploaded documents  
- **Responsive UI** with **shadcn/ui**  
- **Form Validation** using **React Hook Form & Zod**  

## 🛠️ Technologies Used  
- **Frontend:** React, shadcn/ui, React Hook Form, Zod  
- **Backend & Database:** Supabase  
- **Authentication:** Clerk  
- **Deployment:** Vercel  

## 🔧 Installation & Setup  
Follow these steps to set up the project locally:  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/hirrd.git
cd hirrd

2️⃣ Install Dependencies

npm install


3️⃣ Set Up Supabase

Create a Supabase project
Set up the required database tables (jobs, users, applications, resumes)
Configure Supabase Auth


4️⃣ Configure Environment Variables
Create a .env file and add:

VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_secret_key




5️⃣ Start the Development Server

npm run dev






