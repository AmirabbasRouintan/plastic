<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=800&color=2196F3&center=true&vCenter=true&width=600&height=60&lines=Plastic+-+Inventory+Management+System" alt="Typing Animation" />
</div>

<p align="center">
  A warehouse and production management web application for a plastic manufacturing company. Built with React and Node.js.
</p>

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

</div>

## Features

<div align="center">

- **User Authentication** — Register and login to access the panel
- **Product Management** — Add new product pallets with auto-calculated pricing and material usage
- **Warehouse Dashboard** — View real-time warehouse stats (raw materials, total items, pallets)
- **Barcode Generation** — Generate and download barcodes for products as PDF
- **Persian Language UI** — Full Persian (Farsi) interface with IranYekan font

</div>

## Tech Stack

<div align="center">

| Frontend | Backend |
|----------|---------|
| React 18 | Node.js + Express |
| Vite 5 | MySQL |
| Tailwind CSS 3 | bcrypt |
| NextUI 2 | JsBarcode / bwip-js |
| React Router 6 | jsPDF |
| Framer Motion | |

</div>

## Screenshots

![Screenshot 2024-11-14 205625](https://github.com/user-attachments/assets/271952f6-5534-40e9-949d-96266019928e)
![Screenshot 2024-11-14 205639](https://github.com/user-attachments/assets/cd73552e-f2a4-4630-aa07-23309e6e990d)
![Screenshot 2024-11-14 205725](https://github.com/user-attachments/assets/ebd1e309-e3f6-482b-b9af-66bfee21df81)
![Screenshot 2024-11-14 205742](https://github.com/user-attachments/assets/d53bbe46-1914-4117-99d3-1e8e02a37a05)
![Screenshot 2024-11-14 205805](https://github.com/user-attachments/assets/3857dddc-e3a3-4648-89d4-42ee9ae762c6)
![Screenshot 2024-11-14 205854](https://github.com/user-attachments/assets/4e01b7d5-d740-4684-8385-c2f2f8b2e4ff)

## Getting Started

### Prerequisites

- Node.js
- MySQL

### Backend Setup

```bash
cd backend
npm install
```

Configure your database connection in `backend/.env`:

```
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=plastic
DB_PORT=3306
```

Start the server:

```bash
npm start
```

The API runs on `http://localhost:3000`.

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The app is available at `http://localhost:80`.

<div align="center">

## API Endpoints

| Method | Route | Description |
|--------|-------|-------------|
| POST | `/api/register` | Register a new user |
| POST | `/api/login` | User login |
| POST | `/api/add-product` | Add a new product |
| POST | `/api/update-warehouse` | Update warehouse inventory |
| GET | `/api/get-products` | Get all products |
| GET | `/api/get-warehouse` | Get warehouse data |
| GET | `/api/get-product/:barcode` | Get product by barcode |

</div>
