
# ChordExplorer 🎵

**ChordExplorer** is an interactive web-based tool designed to help musicians and composers experiment with and visualize chord progressions. The app combines a Python backend with an Angular frontend to create a seamless and dynamic user experience. Using Docker Compose, the entire application is containerized for easy setup and deployment.

---

## Features

- 🎹 **Interactive Chord Input**: Select or input chords and hear them in real-time.
- 🎶 **Scale and Key Selection**: Choose a key and scale, with suggested chords to guide your progressions.
- 📈 **Progression Visualization**: See a clear timeline of your chord transitions.
- 💾 **Save and Load**: Store your favorite progressions and revisit them anytime.
- 🥁 **Rhythm and Audio Customization**: Apply rhythms and change instrument sounds for unique playback.

---

## Tech Stack

- **Backend**: Python (Flask or FastAPI)
- **Frontend**: Angular with TypeScript
- **Containerization**: Docker and Docker Compose
- **Database**: SQLite (or your choice of database for saved progressions)
- **Optional**: MIDI file handling library for export features

---

## Getting Started

### Prerequisites

- **Docker** and **Docker Compose**
- **Optional**: MIDI device for live input

### Installation

#### Clone the Repository

```bash
git clone https://github.com/your-username/ChordExplorer.git
cd ChordExplorer
```

#### Build and Run with Docker Compose

1. Build and start the containers:

   ```bash
   docker-compose up --build
   ```

2. Access the app:
   - Backend: `http://localhost:5000`
   - Frontend: `http://localhost:4200`

#### Stop and Remove Containers

```bash
docker-compose down
```

---

## Project Structure

```
ChordExplorer/
├── backend/
│   ├── app.py                # Main Python app
│   ├── requirements.txt      # Backend dependencies
│   └── Dockerfile            # Backend Dockerfile
├── frontend/
│   ├── package.json          # Frontend dependencies
│   ├── angular.json          # Angular project config
│   └── Dockerfile            # Frontend Dockerfile
├── docker-compose.yml        # Docker Compose config
└── README.md                 # Project documentation
```

---

## Usage

1. Access the app at `http://localhost:4200`.
2. Select a key and scale from the dropdown menu.
3. Input chords via the virtual keyboard or chord palette.
4. Customize playback and export progressions as MIDI files.

---

## Roadmap

- 🔜 **Interactive Tutorials**: Teach chord theory and progression building.
- 🔜 **Integration with MIDI Devices**: Enable live input and playback.
- 🔜 **Advanced Export Features**: Allow export of progressions to DAWs like Logic Pro.

---

## Contributing

Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy jamming! 🎶
