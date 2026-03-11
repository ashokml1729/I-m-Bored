# 🥱 I'm Bored

A web app that suggests random activities when you're bored, powered by the [Bored API](https://bored-api.appbrewery.com). Filter activities by type and number of participants to find something that suits you.

## 📖 How It Works

- On page load, a **random activity** is fetched and displayed automatically
- Use the dropdowns to filter by **activity type** and **number of participants**
- Hit **Go** to get a matching activity
- If no activity matches your filter, an error message is shown

## 🗂️ Project Structure

```
├── views/
│   └── index.ejs         # Main HTML template (EJS)
├── public/
│   └── style.css         # Styling
├── index.js              # Express server & API logic
├── package.json          # Dependencies
└── package-lock.json     # Lockfile
```

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed

### Installation

```bash
# Clone the repo
git clone https://github.com/ashokml1729/api-integration.git

# Navigate into the project
cd api-integration

# Install dependencies
npm install

# Start the server
node index.js
```

Then open your browser and go to:

```
http://localhost:3000
```

## 🛠️ Built With

- **Node.js** — Runtime environment
- **Express.js** — Web server framework
- **Axios** — HTTP requests to the Bored API
- **EJS** — Templating engine for dynamic HTML
- **CSS3** — Styling and responsive layout

## 🌐 API Used

[Bored API](https://bored-api.appbrewery.com) — provides random activity suggestions with filtering by type and participants.

| Endpoint                          | Description                                     |
| --------------------------------- | ----------------------------------------------- |
| `GET /random`                     | Fetch a completely random activity              |
| `GET /filter?type=&participants=` | Filter activities by type and participant count |

## 📄 License

This project is open source and free to use.
