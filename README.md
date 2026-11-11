# AIOT Project: road_to_BlockChain

Web application for supply chain traceability and warehouse operations, built with React and Node.js.

## Features (pages)

* Order tracking for operators and for customers, with map view
* Camera monitoring, camera based warehouse inbound and outbound
* Warehouse in and out, mobile shelf putaway, QR scanner
* Temperature dashboard
* Product management and product information
* Supplier and supermarket receiving
* Role based dashboard

## Tech stack

* Frontend: React, Vite, Tailwind CSS, React Router, Chart.js, Leaflet, Google Maps
* Backend: Node.js, Express, PostgreSQL (`pg`)

## Structure

```
road_to_BlockChain/
  frontend/   React app (src/pages, src/components)
  backend/    Express API (src/controllers, src/routes, src/models)
```

## Run locally

Backend:

```bash
cd road_to_BlockChain/backend
npm install
# create .env with PSQLDB_CONNECTIONSTRING=<your PostgreSQL connection string> and PORT
npm start
```

Frontend:

```bash
cd road_to_BlockChain/frontend
npm install
# create .env with VITE_GOOGLE_MAPS_API_KEY=<your key>
npm run dev
```
