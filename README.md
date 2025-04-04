
#  OrbitalBite – Frontend

This is the frontend of **OrbitalBite**, a modern food ordering platform for restaurants. Built with React, this interface consumes APIs from the Django backend and offers a clean, responsive user experience.

---

## Tech Stack

- React 18+
- JavaScript (or TypeScript - optional)
- Axios
- React Router
- Vite or Create React App
- Tailwind CSS (optional)

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/orbitalbite/orbitalbite-frontend.git
cd orbitalbite-frontend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Environment Variables

Create a `.env` file in the root directory:

```bash
REACT_APP_API_URL=http://127.0.0.1:8000/api
```

> Replace the URL if your backend is hosted elsewhere.

### 4. Run the Development Server

```bash
npm start
```

The app will run at:  
� `http://localhost:3000`

---

## Available Routes

| Path        | Description              |
|-------------|--------------------------|
| `/`         | Home page                |
| `/menu`     | Menu and categories      |
| `/basket`   | View and edit your cart  |
| `/item/:id` | Item detail page         |

---

## Project Structure

```
orbitalbite-frontend/
├── public/
│   └── index.html
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   ├── utils/
│   ├── App.js
│   ├── index.js
│   ├── style.css
│   └── user-style.css
├── .env.example
├── LICENSE
├── package.json
└── README.md
```

---

## Styling

You can style the app using:
- Tailwind CSS (recommended)
- Styled Components
- CSS Modules

---

## Running Tests (Coming Soon)

```bash
npm test
```

---

## Contributing

1. Fork the repository  
2. Create a new branch: `git checkout -b feature/your-feature`  
3. Make your changes and commit: `git commit -m "Add your feature"`  
4. Push to your branch: `git push origin feature/your-feature`  
5. Open a Pull Request

---

## License

This project is licensed under the Apache License. See the `LICENSE` file for more information.
