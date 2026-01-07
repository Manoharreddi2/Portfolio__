🏠 AI Interior Design Remodel App

An AI-powered desktop application that transforms interior space images into redesigned layouts using prompt-based AI image generation via the Replicate API.

🚀 Features

🖼️ Upload interior room images (PNG / JPG / JPEG)

✍️ Enter custom design prompts (modern, minimal, luxury, etc.)

🤖 AI-powered interior remodeling using Replicate models

⏳ Real-time processing status updates

📸 Displays both original and remodeled images

🧩 Clean desktop UI built with DelphiFMX (FireMonkey)

🛠️ Tools & Tech Stack

Language: Python

AI Platform: Replicate API

AI Model: Interior Design Image-to-Image Model

GUI Framework: DelphiFMX (FireMonkey)

Image Handling: Python Image/File APIs

API Integration: REST-based AI inference


📂 Project Structure


├── main.py                  # Main application code
├── Air.style                # UI styling file
├── README.md                # Project documentation
└── output_images/           # Generated remodeled images



⚙️ Setup & Installation
1️⃣ Clone the Repository
git clone https://github.com/Manoharreddi2/Portfolio__.git
cd Portfolio__

2️⃣ Install Dependencies
pip install replicate delphifmx

3️⃣ Set Replicate API Token

Create an API token from Replicate and set it as an environment variable.

macOS / Linux

export REPLICATE_API_TOKEN="your_api_token_here"


Windows (PowerShell)

setx REPLICATE_API_TOKEN "your_api_token_here"


⚠️ Restart the terminal after setting the token.

4️⃣ Run the Application
python main.py

Version Control: Git & GitHub

IDE: Visual Studio Code
