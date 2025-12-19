🧞‍♂️ GITAM Genie - Your University Assistant

GITAM Genie is a rule-based chatbot designed to help students at GITAM University (Visakhapatnam) navigate campus life effortlessly. From bus timings to library schedules and exam procedures, the Genie has all the answers in one interactive interface.

✨ Features
🔐 Secure Access: Login page with Guest mode support.

🚌 Transport Hub: Real-time access to Vizag campus bus routes and timings.

📚 Knowledge Base: Instant answers regarding Library, Courses, and Hostels.

⚡ Quick Actions: One-tap buttons for the most common student queries.

🎨 Branded UI: A customized Streamlit interface using GITAM's signature colors.

🛠️ Tech Stack
Frontend: Streamlit (Python-based web framework)

Logic Engine: Rule-based keyword matching (Python)

Data Storage: JSON (Modular knowledge base)

Styling: Custom CSS and Base64 image encoding

📂 Project Structure

The project is divided into modular files for easy scalability:

Plaintext

├── app.py              # Main Streamlit application (UI & Routing)
├── knowledge.json      # Knowledge base containing all Q&A data
├── splash_screen.png   # Login page background image
├── bot_pic.png         # Genie avatar for chat interface
└── README.md           # Project documentation

📖 How it Works

The chatbot uses a Keyword Matching Algorithm. When a user types a query, the system:

Normalizes the input to lowercase.

Scans the knowledge.json file for matching keywords.

Returns the structured response along with the official university source link.
