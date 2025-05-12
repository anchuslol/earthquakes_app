# Earthquakes App

Welcome to the **Earthquakes App** repository! This application is designed to provide real-time earthquake data, visualize seismic activity, and offer insights into global tectonic movements. Built with cutting-edge technologies, it serves as a powerful tool for researchers, enthusiasts, and anyone interested in understanding the Earth's dynamic behavior.

![Earthquake Dashboard Banner](img\output_20250512_175112.jpg)

---

## Features

- **Real-Time Data**: Fetch live earthquake data from reliable sources.
- **Interactive Maps**: Visualize seismic activity on dynamic, user-friendly maps.
- **Custom Filters**: Filter earthquakes by magnitude, depth, location, and time.
- **Notifications**: Get alerts for significant seismic events.
- **Analytics Dashboard**: Analyze trends and patterns in earthquake occurrences.

---

## Tech Stack

- **Frontend**: 
  - Framework: [React.js](https://reactjs.org/)
  - Styling: [Tailwind CSS](https://tailwindcss.com/)
  - Mapping: [Leaflet.js](https://leafletjs.com/)

- **Backend**:
  - Language: [Python](https://www.python.org/)
  - Framework: [FastAPI](https://fastapi.tiangolo.com/)
  - Database: [PostgreSQL](https://www.postgresql.org/)

- **APIs**:
  - [USGS Earthquake API](https://earthquake.usgs.gov/fdsnws/event/1/)
  - [OpenStreetMap](https://www.openstreetmap.org/)

- **Deployment**:
  - Platform: [Docker](https://www.docker.com/)
  - Cloud: [AWS](https://aws.amazon.com/)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/earthquakes_app.git
   cd earthquakes_app
   ```

2. Set up the backend:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   uvicorn main:app --reload
   ```

3. Set up the frontend:
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. Access the app at `http://localhost:3000`.

---

## Usage

1. Open the app in your browser.
2. Explore the map to view recent earthquakes.
3. Use filters to customize your search.
4. Analyze data trends in the dashboard.

---

## Contributing

We welcome contributions! To get started:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your fork.
4. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or feedback, please reach out to:

- **Author**: Pablo Anchustegui
- **Email**: pabloanchu@gmail.com
- **GitHub**: 

---

Thank you for exploring the Earthquakes App! 🌍