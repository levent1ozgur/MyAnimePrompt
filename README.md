# MyAnimePrompt: AI Anime Recommendation Prompt Generator

**MyAnimePrompt** is a free, browser-based tool that transforms your **MyAnimeList (MAL) anime export data** into a structured Markdown prompt designed for use with Large Language Models (LLMs).

Instead of manually explaining your anime preferences to an AI, MyAnimePrompt processes your completed anime history, extracts relevant information such as titles and ratings, and turns it into a structured representation of your viewing preferences.

You can then copy the generated prompt into an LLM such as ChatGPT and ask it to recommend new anime based on your existing watch history.

The goal is simple:

**Export your MAL data → Upload it → Generate a prompt → Give it to an LLM → Discover new anime.**

---

## ✨ Key Features

### 📥 Easy MyAnimeList Data Import

MyAnimePrompt works with the XML export provided by MyAnimeList.

The process is simple:

* Export your anime list from MyAnimeList.
* Upload the XML file to MyAnimePrompt.
* Let the browser process your anime history.
* Generate a structured Markdown prompt.

No manual copying and pasting of hundreds of anime titles is required.

---

### 🧩 Automated Anime List Processing

The tool parses your MAL export and extracts relevant information from your completed anime list.

Depending on the available data, the generated prompt can incorporate information such as:

* Anime titles
* User ratings
* Completed anime
* Grouped related titles

This provides an LLM with a more structured representation of your viewing history than a simple unorganised list.

---

### 📊 Title Grouping & Rating Analysis

Related anime titles can be grouped together to provide a cleaner representation of your preferences.

For example, multiple entries belonging to the same franchise or series can be treated as related titles rather than completely independent recommendations.

The tool can also calculate average ratings for grouped titles, helping an LLM identify broader patterns in your preferences.

This can make the resulting recommendation prompt more useful when your MAL list contains multiple seasons, sequels, or related entries.

---

### 🎯 Focused Recommendation Prompt

MyAnimePrompt generates a structured Markdown prompt specifically designed to be used with an LLM.

The generated prompt is intended to help an AI understand:

* What anime you have already watched
* Which titles you rated highly
* Which titles you rated poorly
* Your broader viewing preferences
* Which related titles should be considered when generating recommendations

The resulting prompt can be copied into your preferred LLM and used as the basis for personalised anime recommendations.

---

### 🚫 Reduce Repetitive Recommendations

The generated prompt can instruct the LLM to avoid recommending anime that are already represented in your viewing history.

It can also help focus recommendations on new titles rather than simply suggesting sequels, prequels, or closely related entries that you may have already watched.

This is intended to encourage more diverse recommendations and help you discover anime outside your existing watch list.

---

### 📋 One-Click Prompt Copying

Once your Markdown prompt has been generated, you can copy it directly to your clipboard.

The workflow is designed to be:

**Upload → Convert → Copy → Paste into your LLM**

No account or complicated configuration is required.

---

### 📱 Desktop & Mobile Friendly

MyAnimePrompt is designed as a browser-based tool that can be used across different devices.

You can use it on:

* Desktop computers
* Laptops
* Tablets
* Smartphones

This makes it possible to generate recommendation prompts wherever you maintain or access your MyAnimeList data.

---

## 🚀 Getting Started

### 1. Export Your MyAnimeList Data

Visit the MyAnimeList export page and request your anime list export:

[MyAnimeList Export Page](https://myanimelist.net/panel.php?go=export&utm_source=chatgpt.com)

Download your anime list in XML format.

---

### 2. Upload Your XML File

Open MyAnimePrompt and select the XML file exported from MyAnimeList.

The application will read the file and prepare the data for processing.

---

### 3. Convert Your Anime History

Click **Convert to Markdown**.

MyAnimePrompt will process your anime history and generate a structured Markdown prompt containing information derived from your MAL data.

---

### 4. Copy the Generated Prompt

Click **Copy Prompt** to copy the generated Markdown to your clipboard.

---

### 5. Ask an AI for Recommendations

Paste the generated prompt into your preferred LLM.

You can use services such as ChatGPT or another compatible AI assistant and ask for personalised anime recommendations based on your viewing history.

For example, you can ask the AI to:

* Recommend 10 anime you are likely to enjoy.
* Find anime similar to your highest-rated titles.
* Suggest less mainstream titles matching your preferences.
* Identify genres you may enjoy based on your ratings.
* Recommend anime outside your usual viewing habits.

---

## 🔒 Privacy First

MyAnimePrompt is designed with a **local-first processing model**.

Your MyAnimeList XML export is processed directly in your browser rather than being uploaded to a MyAnimePrompt backend.

This means:

* No MyAnimeList login is required.
* Your MAL credentials are never requested.
* Your exported XML file is not intentionally uploaded to a MyAnimePrompt server.
* Your anime list remains on your device while it is being processed.
* The generated prompt is created locally in your browser.

The generated Markdown prompt is only sent to an AI service if **you choose to copy and paste it into that service yourself**.

> **Privacy note:** Once you manually paste your generated prompt into a third-party LLM, that service's own privacy policy and data-handling practices apply.

---

## ⚙️ How It Works

MyAnimePrompt follows a straightforward client-side workflow:

```text
MyAnimeList
     │
     │ Export XML
     ▼
MAL XML File
     │
     │ Upload
     ▼
MyAnimePrompt
     │
     │ Parse & Process
     ▼
Completed Anime + Ratings
     │
     │ Group & Organise
     ▼
Structured Markdown Prompt
     │
     │ Copy
     ▼
Your Preferred LLM
     │
     ▼
Personalised Anime Recommendations
```

The application acts as a bridge between your MyAnimeList history and an LLM.

Rather than building its own recommendation engine, MyAnimePrompt focuses on converting your existing anime data into a format that an AI model can understand and use for recommendation tasks.

---

## 🛠️ Technical Details

* **Platform:** Browser-based web application
* **Input:** MyAnimeList XML export
* **Output:** Structured Markdown prompt
* **Processing:** Client-side
* **Authentication:** Not required
* **Backend:** No MyAnimePrompt server required for XML processing
* **AI Provider:** User-selected LLM
* **Data Transfer:** The generated prompt is only sent to an LLM when the user manually provides it to that service
* **Compatibility:** Desktop and mobile browsers

---

## 💡 Use Cases

### Anime Fans

Discover new anime based on your existing viewing history rather than relying solely on generic popularity lists.

### MyAnimeList Users

Turn a large MAL anime list into a structured format that can be easily understood by an AI assistant.

### AI Enthusiasts

Experiment with LLM-powered recommendation systems using your own personal data.

### Anime Researchers

Use an LLM to analyse patterns in your viewing history, such as recurring genres, themes, studios, or preferences.

### Content Creators

Generate recommendation ideas and explore connections between different anime based on a curated viewing history.

---

## 🎯 What Makes MyAnimePrompt Useful?

Traditional anime recommendation systems often rely on predefined algorithms, popularity rankings, or collaborative filtering.

MyAnimePrompt takes a different approach.

It allows you to provide your **own viewing history as context to an LLM**, giving the AI more information about your individual preferences.

This makes it possible to experiment with recommendation prompts that go beyond simple:

> "I liked this anime. What should I watch next?"

Instead, the AI can receive a structured overview of your broader viewing history and ratings.

---

## ⚠️ Limitations

MyAnimePrompt has several limitations:

* Recommendations depend on the quality and completeness of your MyAnimeList data.
* The tool does not directly generate recommendations itself.
* Recommendation quality depends on the LLM you use.
* Different LLMs may produce different recommendations from the same prompt.
* MyAnimeList data may contain incomplete or outdated information.
* Grouping related anime titles may not always perfectly represent how you personally view a franchise.
* A stable internet connection is required to access the web application and your chosen LLM service.

---

## 👥 Ideal For

MyAnimePrompt is designed for:

* **Anime fans** looking for personalised recommendations
* **MyAnimeList users** with large watch histories
* **AI enthusiasts** experimenting with LLM-based recommendations
* **Anime researchers** analysing viewing preferences
* **Content creators** looking for recommendation ideas

---

## 💡 Pro Tip

Keep your MyAnimeList account updated before exporting your data.

The more accurately your MAL list reflects your actual viewing history and ratings, the more useful the generated prompt can be when you ask an LLM for recommendations.

For even better results, experiment with different instructions after pasting the generated prompt. Ask the AI to prioritise hidden gems, avoid mainstream titles, focus on specific genres, or recommend anime that are significantly different from what you normally watch.

---

## 📄 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for the full licence text.

---

## 👨‍💻 Author

**Levent Özgür**

GitHub: [levent1ozgur](https://github.com/levent1ozgur?utm_source=chatgpt.com)

MyAnimePrompt: [Visit MyAnimePrompt](https://myanimeprompt.netlify.app/?utm_source=chatgpt.com)
