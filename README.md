
<div align="center">

# 📚 AI-Nable
### Making Learning More Accessible with Generative AI

**An AI-powered learning platform designed for students with different learning needs.**

Built during an AWS Generative AI Hackathon.

[🎬 Watch Demo](https://www.youtube.com/watch?v=6THwhBVxuzc) • [🌐 My Portfolio](https://anain0404.github.io/anvesha-portfolio/)

</div>

---

## 💡 The Idea

Learning shouldn't be harder just because information is presented in a format that doesn't work for everyone.

Students with ADHD, dyslexia, and other learning differences may find traditional, text-heavy educational materials difficult to process.

We built **AI-Nable**, with its student-facing application **SnapStudy**, to explore how generative AI could make educational content easier to understand, more interactive, and more accessible.

Instead of expecting every student to learn in the same way, our platform allows students to interact with educational materials through simplified text, audio narration, and conversational support.

---

## ✨ What SnapStudy Does

### 📄 Intelligent Document Processing
Upload educational PDFs and images, then extract the content using Amazon Textract.

### 🧠 AI-Powered Text Simplification
Transform complex educational materials into three levels of simplified content:

- **Level 1:** Basic simplification
- **Level 2:** Simplified explanations with bullet points
- **Level 3:** Step-by-step breakdowns

### 🔊 Text-to-Speech Learning
Listen to educational content through Amazon Polly's natural-sounding voice narration.

### 💬 Interactive AI Assistance
Ask questions about uploaded learning materials and receive AI-generated explanations.

### 🎨 Accessible Learning Experience
A student-friendly interface featuring Tobi, our bear mascot, designed to make the learning experience feel more approachable.

### 📚 Personalized Learning Tools
Explore visual storytelling, saved lessons, and previous uploads.

---

## 🛠️ Tech Stack

| Category | Technologies |
| :--- | :--- |
| Frontend | Flutter, Dart |
| Backend | Python, FastAPI |
| Generative AI | Amazon Bedrock, Claude 3 Haiku |
| Document Processing | Amazon Textract |
| Text-to-Speech | Amazon Polly |
| File Storage | Amazon S3 |
| Product Design | Figma |
| Cloud Infrastructure | AWS |

---

## 🏗️ System Architecture

The application uses a Flutter frontend connected to a FastAPI backend that communicates with AWS services.

```text
             STUDENT
                |
                v
        Flutter Mobile App
                |
                v
          FastAPI Backend
                |
       +--------+---------+
       |        |         |
       v        v         v
   Textract   Bedrock    Polly
       |        |         |
       v        v         v
    Extract   Simplify   Generate
     Text     Content     Audio
       |        |         |
       +--------+---------+
                |
                v
       Accessible Learning
           Experience
```

**How it works:**

1. A student uploads an educational document.
2. Amazon Textract extracts text from the document.
3. Amazon Bedrock processes and simplifies the content.
4. Students choose the level of explanation that works for them.
5. Amazon Polly converts content into audio.
6. Students can interact with the material through the app's learning interface.

---

## 👩‍💻 My Contributions

### Product Lead | SnapStudy

I worked with a four-person cross-functional team to develop SnapStudy, focusing on the intersection of AI, accessibility, product development, and user experience.

My contributions included:

- **Product Discovery:** Identified accessibility challenges faced by students with different learning needs and translated them into product requirements.
- **UI/UX Design:** Developed Figma prototypes and helped shape an approachable, student-centered learning experience.
- **AI Product Development:** Collaborated on the AI-powered text simplification pipeline and its integration into the learning experience.
- **Model Iteration:** Helped improve text-simplification accuracy by **35%** through iterative testing and refinement.
- **Team Leadership:** Coordinated product development across the team, from initial concept to hackathon prototype.

This project gave me experience in translating user needs into technical features and building AI-powered applications with accessibility in mind.

---

## 🎬 Demo

Watch our application walkthrough:

**[▶ Watch the AI-Nable Demo on YouTube](https://www.youtube.com/watch?v=6THwhBVxuzc)**

The demonstration covers:

- The SnapStudy interface and Tobi mascot
- Uploading educational materials
- AI-powered text extraction and simplification
- Audio narration
- Interactive learning features

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Flutter SDK
- An AWS account
- Access to Amazon Textract, Bedrock, and Polly
- AWS credentials configured for the required services

### 1. Clone the Repository

```bash
git clone https://github.com/Anay-Misra/AI-Nable.git
cd AI-Nable
```

### 2. Backend Setup

Create and activate a Python virtual environment:

```bash
python -m venv venv
source venv/bin/activate
```

On Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure your AWS credentials and environment variables using the project's environment configuration.

**Never commit AWS access keys or secret keys to GitHub.**

Start the backend:

```bash
cd backend
uvicorn main:app --reload --port 8000
```

### 3. Frontend Setup

In a separate terminal, navigate to the frontend directory:

```bash
cd frontend
flutter pub get
flutter run
```

**Note:** Verify directory paths and dependency installation commands against the repository's current structure before running the application.

---

## 🧪 Testing & Evaluation

We focused on evaluating the learning experience and reliability of the AI pipeline.

Key areas included:

- Document extraction from educational PDFs
- Text simplification across different complexity levels
- Accessibility and readability of generated explanations
- Audio narration and playback
- Error handling for unsupported documents
- Usability of the student-facing interface

Through iterative product and AI development, we improved text-simplification accuracy by **35%**.

---

## 🔮 Future Improvements

Potential next steps include:

- More personalized simplification based on user preferences
- Improved visual explanations and learning aids
- Better support for offline learning
- Expanded accessibility controls
- Additional testing with learners and educators
- More detailed evaluation of comprehension and usability

---

## 🤝 Team

Built during an AWS Generative AI Hackathon.

**Team Members:**
- Anay Misra
- Sanskriti
- Anvesha Nain
- Saksham

---

## ☕ Connect With Me

I'm interested in building AI-powered products that make technology more accessible and useful.

[🌐 Portfolio](https://anain0404.github.io/anvesha-portfolio/) • [💼 LinkedIn](https://www.linkedin.com/in/anvesha-nain-a14033223/) • [📧 Email](https://mail.google.com/mail/?view=cm&fs=1&to=nain.anvesha4@gmail.com)

*Brewing ideas into products that make a difference.*
