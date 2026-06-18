English Foundations - Module 1: The Power Pair

An interactive, single-file web application designed to help adult ESL learners—specifically native Turkish speakers—overcome syntax barriers and transition from an SOV (Subject-Object-Verb) to an SVO (Subject-Verb-Object) mindset.

🎯 Project Overview

This module was custom-built for adult A0/A1 learners to correct the common "Turklish" habit of placing verbs at the end of sentences. By utilizing a highly visual, tactile drag-and-drop interface, learners build muscle memory for standard English sentence structures using high-utility vocabulary related to business, travel, and daily life.

✨ Key Features

🎨 Color-Coded Grammar: Visual reinforcement of sentence structures.

🟦 Blue: Subjects / People

🟥 Red: Verbs / Actions

🟩 Green: Objects / Nouns

🪤 The "Turklish" Trapdoor: Custom validation logic that anticipates native language interference. If a user attempts an SOV structure (e.g., Subject + Object + Verb), the UI triggers a specific error state, gently explaining the English rule.

🧠 Cognitive Load Management: Starts with basic Subject + Verb (Levels 1-2) before introducing Objects and distractors (Levels 3-30).

🧩 Distractor Mechanics: Word banks include grammatically or contextually incorrect words to ensure active learning rather than passive guessing.

📱 Fully Responsive & Touch-Ready: Utilizes both HTML5 Drag-and-Drop for desktop and Tap-to-Move fallback logic for seamless mobile/tablet usage.

🛠 Tech Stack

This project is built to be extremely lightweight and requires no build pipeline or server-side rendering.

HTML5 (Structure)

Vanilla JavaScript (Game logic, state management, drag-and-drop API)

Tailwind CSS via CDN (Styling, responsive design, animations)

🚀 Installation & Usage

Because this is a zero-dependency, single-file application, setup is instant.

Clone the repository:

git clone https://github.com/yourusername/english-power-pair.git


Navigate to the project directory.

Open lesson1_module.html directly in any modern web browser (Chrome, Safari, Firefox, Edge).

Playing the Game

Click Start Module on the landing page.

Read the target sentence in Turkish at the top of the screen.

Drag the correct English words from the Word Bank into the Your Sentence drop zone.

Arrange them in the correct S-V-O order.

If you make a mistake, use the Reset Blocks button or simply drag words back to the bank.

Navigate between the 30 levels using the top arrow controls.

📂 File Structure

├── index.html   # Main application file (HTML, CSS, JS)
└── README.md             # Project documentation


🧠 Pedagogical Methodology

This application was designed around the specific needs of an adult learner running multiple businesses.

No Childish Graphics: A clean, professional UI suitable for adults.

High-Utility Vocabulary: Focuses on words needed for social media, car resale, real estate, and travel (e.g., client, video, flight, apartment).

No Direct Translation Crutches: Forces the user to assemble the English sentence from scratch rather than translating word-by-word.

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request
