# Business-finder
A lightweight, single-page web application that allows users to search for local businesses, filter by geographic radius, and export location data directly to a CSV file. Built using HTML5, Tailwind CSS, and pure JavaScript, it communicates directly with the Google Places API (New) without requiring a backend server or proxy.

✨ Features
🔍 Targeted Local Search: Query businesses by keyword/type, location, and customizable search radius.

⚡ Direct API Calls: Leverages the latest Google Places API (New) directly from the frontend.

🔑 Built-In API Testing: Features an in-app "Test API Key" button to validate your key and quotas before running broad searches.

📄 Pagination Support: Automatically handles page tokens to retrieve up to 60 results per search.

📥 One-Click CSV Export: Export business names, addresses, ratings, and key contact details into a structured .csv file for easy lead generation or CRM import.

🎨 Modern Responsive UI: Clean, mobile-friendly interface designed with Tailwind CSS.

🚀 Quick Start
Clone or Download the Repository:

Bash
git clone https://github.com/your-username/google-places-finder.git
Open the App:
Simply open index.html in any web browser. No local server setup (npm install) required!

Provide Your API Key:

Generate a Google Places API key via the Google Cloud Console.

Ensure the Places API (New) is enabled on your project.

Enter your key into the app UI, hit Test API, and start searching.

🛠️ Built With
HTML5 & Vanilla JavaScript (ES6+)

Tailwind CSS (via CDN)

Google Places API (New)

🔒 Security & Usage Note
Since this app executes API calls directly from the browser, make sure to restrict your Google Places API key in the Google Cloud Console (e.g., restrict by HTTP referrer or API type) to prevent unauthorized usage.
