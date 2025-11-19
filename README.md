Certificate Generator

A simple automation tool that generates certificates for multiple participants.
Just provide:
Certificate template (PNG/JPG/PDF)
List of participant names
Font file (e.g., .ttf)
X & Y coordinates where the name should be placed
The script will automatically create individual certificates for each participant.

🚀 Features

Automatically places each participant’s name on the certificate.
Supports custom fonts.
Adjustable text coordinates.
Generates certificates in bulk.
Saves all output certificates automatically.

📂 How It Works

Add your template to the project folder.
Add your names list (TXT/CSV).
Choose your font
Set the coordinates for the name placement.
Run the script — certificates for all participants will be generated.

🛠️ Technologies Used

Python
Pillow (PIL) for image editing
ReportLab (optional for PDF handling)

▶️ Run the Project

python generate_certs.py
