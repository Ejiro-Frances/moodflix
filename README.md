# 🎬 MoodFlik

MoodFlik is a sleek movie discovery app built with **React** and **Tailwind CSS**. You can search for any movie or browse trending ones — perfect for finding what to watch next.

> ⚠️ This is a **follow-along project** based on a tutorial by [JavaScript Mastery Pro](https://youtu.be/dCLhUialKPQ?si=JK5kBCx6aSvsHUwJ). I do not claim ownership of the code or design — this was built strictly for **educational purposes and personal learning**.

## 🚀 Features

- 🔍 Search for movies in real-time
- 📈 View trending and popular titles
- 💾 Store search history using **Appwrite**
- 💨 Fast and responsive UI powered by Tailwind CSS
- ⚛️ Built with modern React practices

## 🛠 Tech Stack

- **Frontend:** React, Tailwind CSS
- **Backend:** Appwrite (for storing search data)
- **API:** The Movie Database (TMDb) API

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ejiro-Frances/moodflik.git
   cd moodflik
   ```
2. Install dependencies:

```bash
npm install
```

3. Start the development server

```
npm run dev
```

4. Get your API key from TMDB

5. Set up Appwrite:

- Create a project on Appwrite

- Add a database and collection for search logs

- Get your Appwrite API key and store it securely in a .env.local file.

- Add your Appwrite environment variables to a .env.local file:

```.env.local
VITE_APPWRITE_PROJECT=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id

```

## 🙏 Credits

This project is based entirely on the YouTube tutorial by JavaScript Mastery Pro.
[Watch the full video here:](https://youtu.be/dCLhUialKPQ?si=JK5kBCx6aSvsHUwJ)

📄 License
This project is for educational use only and not intended for commercial purposes.
