# React Form State Manager with `useState`

A small React + Vite project that demonstrates how to handle multiple form inputs using a **single object state** and dynamically update fields via a generic `handleChange`. It also logs all collected data when the user clicks **Enviar**. (Project interface in Portuguese)

---

## Features

- Manage multiple inputs with a single `useState` object (`nome`, `sobrenome`, `cidade`, `rua`, `bairro`, `numero`)
- Generic `handleChange` updates each field dynamically by name
- “Enviar” button triggers a function that prints the full form data to the console

---

## Tech Stack

- **React** with hooks (`useState`)
- **Vite** for build and development
- **JavaScript** + basic CSS styling

---

## Screenshots

![Screenshot](src/assets/Screenshot-1.png)
![Screenshot](src/assets/Screenshot-2.png)

## Getting Started

Clone the repository and run locally:

```bash
# 1) Clone the repo
git clone https://github.com/fabioesilveira/Form-StateManager.git

# 2) Navigate to project folder
cd Form-StateManager

# 3) Install dependencies
npm install

# 4) Start the development server
npm run dev

