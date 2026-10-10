Aeroflex AI Studio
A responsive AI website starter with:
Gemini-powered chat through a server-side API call
Browser-based text-to-speech preview
Mobile-responsive dark interface
API status and setup page
Requirements
Node.js 18 or newer
A Gemini API key from Google AI Studio
Run locally
Extract this ZIP.
Install Node.js on a computer.
In this folder, copy .env.example to a new file named .env.
Open .env and replace PASTE_YOUR_GEMINI_API_KEY_HERE with your API key.
In a terminal in this folder, run:
npm install
npm start
Open http://localhost:3000.
Important security notes
Do not put the API key in public/index.html, browser JavaScript, or a public repository.
Do not upload the .env file.
For online use, deploy the Node.js app to a host that supports server-side environment variables. Add GEMINI_API_KEY in the host's private environment-variable settings.
API quotas, free tier availability, model access, and billing are controlled by Google and may change.
Voice Studio uses the browser/device speech engine and does not generate downloadable MP3 files.
If you only have an Android phone
The HTML interface can be viewed as a static page, but live AI chat requires the backend server to run somewhere. For a live public website, deploy this project to a Node.js hosting service and set the API key as a private environment variable. Do not paste the key into a public HTML file.
