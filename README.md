


Roxiller Syetems - MERN challenge


### Backend Setup

3. **Create a `.env` file in the backend directory and add your MongoDB URI:**

   ```plaintext
   PORT=5000
   MONGO_URI="your_mongodb_uri"
   NODE_ENV=production
   FRONTEND_URL=http://localhost:3000
   ```

4. **Start the backend server:**

   ```bash
   npm start
   ```

### Frontend Setup

1. **Navigate to the frontend directory:**

   ```bash
   cd ../frontend
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the frontend development server:**

   ```bash
   npm start
   ```

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Use the dropdown to select a month and the search bar to filter transactions by title.
3. View the transactions in the table, along with the pie chart, bar chart, and statistics section.

## API Endpoints

1-Transactions

- **GET /api/v1/transactions**: Retrieve transactions with optional filters for month, search, and pagination.

2-Bar Chart Data

- **GET /api/v1/bar-chart**: Retrieve data for the bar chart visualization.

3-Project Structure

```plaintext
Assignment-Roxiller System/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── .env
│   └── ...
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
│   ├── public/
│   ├── .env
│   └── ...
│
├── .gitignore
├── README.md
└── ...
```