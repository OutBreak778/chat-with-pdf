# **AI-Powered PDF Workspace and Text Editor**

An advanced platform for managing, viewing, and editing PDF files with integrated AI-powered text generation. This project streamlines workflows by combining a modern text editor with robust file management and AI assistance.

---

## **Features**

### **Dashboard**
- A centralized hub to manage all uploaded files.
- Skeleton loaders for smooth user experience while data is being fetched.

### **AI-Powered Text Editor**
- Built using [TipTap Editor](https://tiptap.dev/), supporting rich text formatting.
- AI integration for generating and refining content based on user input.
- Loading indicators for AI responses and clean, well-structured output display.

### **PDF Viewer**
- Preview and interact with PDF files side-by-side with the text editor.

### **User Authentication**
- Secured and seamless authentication powered by [Clerk](https://clerk.dev/).

### **File Management**
- Upload, view, and manage PDFs with metadata like file size, type, and upload date.

### **Dynamic Loading**
- Efficient rendering with suspense boundaries and skeleton loaders for components.

---

## **Tech Stack**

### **Frontend**
- [Next.js](https://nextjs.org/) – React-based framework for building user interfaces.
- [TailwindCSS](https://tailwindcss.com/) – Utility-first CSS framework for styling.
- [TipTap Editor](https://tiptap.dev/) – Rich text editor for text editing.

### **Backend**
- [Convex API](https://convex.dev/) – Dynamic data management and serverless backend.

### **AI Integration**
- [OpenAI API](https://openai.com/) – For generating text and answers based on user prompts.

### **Authentication**
- [Clerk.js](https://clerk.dev/) – Secure and scalable user authentication.

---

## **Setup and Installation**

### Prerequisites
Ensure you have the following installed:
- Node.js (v16 or later)
- npm or yarn
- Convex CLI (`npm install -g @convex/cli`)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

### Set up your environment variables :###
NEXT_PUBLIC_CLERK_FRONTEND_API=<Your Clerk Frontend API Key>
GEMINI_API_KEY=<Your OpenAI API Key>
CONVEX_DEPLOYMENT_URL=<Your Convex Deployment URL>

### Folder Structure ### 
.
├── /app
│   ├── /dashboard – Dashboard and file management components
│   ├── /workspaces – Text editor and PDF viewer
│   ├── /settings – User settings
├── /components – Reusable UI components
├── /hooks – Custom hooks for account creation, modal handling, etc.
├── /convex – Convex API functions
├── /public – Static assets
├── /styles – TailwindCSS configuration
├── .env – Environment variables
├── next.config.js – Next.js configuration
└── README.md – This file



Here’s a sample README.md file for your project:

markdown
Copy code
# **AI-Powered PDF Workspace and Text Editor**

An advanced platform for managing, viewing, and editing PDF files with integrated AI-powered text generation. This project streamlines workflows by combining a modern text editor with robust file management and AI assistance.

---

## **Features**

### **Dashboard**
- A centralized hub to manage all uploaded files.
- Skeleton loaders for smooth user experience while data is being fetched.

### **AI-Powered Text Editor**
- Built using [TipTap Editor](https://tiptap.dev/), supporting rich text formatting.
- AI integration for generating and refining content based on user input.
- Loading indicators for AI responses and clean, well-structured output display.

### **PDF Viewer**
- Preview and interact with PDF files side-by-side with the text editor.

### **User Authentication**
- Secured and seamless authentication powered by [Clerk](https://clerk.dev/).

### **File Management**
- Upload, view, and manage PDFs with metadata like file size, type, and upload date.

### **Dynamic Loading**
- Efficient rendering with suspense boundaries and skeleton loaders for components.

---

## **Tech Stack**

### **Frontend**
- [Next.js](https://nextjs.org/) – React-based framework for building user interfaces.
- [TailwindCSS](https://tailwindcss.com/) – Utility-first CSS framework for styling.
- [TipTap Editor](https://tiptap.dev/) – Rich text editor for text editing.

### **Backend**
- [Convex API](https://convex.dev/) – Dynamic data management and serverless backend.

### **AI Integration**
- [OpenAI API](https://openai.com/) – For generating text and answers based on user prompts.

### **Authentication**
- [Clerk.js](https://clerk.dev/) – Secure and scalable user authentication.

---

## **Setup and Installation**

### Prerequisites
Ensure you have the following installed:
- Node.js (v16 or later)
- npm or yarn
- Convex CLI (`npm install -g @convex/cli`)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
Install dependencies:

bash
Copy code
npm install
Set up your environment variables:

Create a .env file in the root directory.
Add the following:
env
Copy code
NEXT_PUBLIC_CLERK_FRONTEND_API=<Your Clerk Frontend API Key>
OPENAI_API_KEY=<Your OpenAI API Key>
CONVEX_DEPLOYMENT_URL=<Your Convex Deployment URL>
Run the development server:

bash
Copy code
npm run dev
Access the application at http://localhost:3000.

Folder Structure
plaintext
Copy code
.
├── /app
│   ├── /dashboard – Dashboard and file management components
│   ├── /workspaces – Text editor and PDF viewer
│   ├── /settings – User settings
├── /components – Reusable UI components
├── /hooks – Custom hooks for account creation, modal handling, etc.
├── /convex – Convex API functions
├── /public – Static assets
├── /styles – TailwindCSS configuration
├── .env – Environment variables
├── next.config.js – Next.js configuration
└── README.md – This file
Usage
Upload a PDF using the Dashboard.
Select a file to open it in the Workspace.
Use the Text Editor to:
Generate AI-powered responses.
Edit text with rich formatting.
Preview your PDF side-by-side with your text edits.
Contributing
Contributions are welcome! To contribute:
 

# Acknowledgments #
Next.js
TailwindCSS
Clerk.js
Google GEMINI API
TipTap Editor
Convex API