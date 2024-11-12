# Plant Shop React App

A simple React application that allows users to manage a plant shop. Users can view all plants, add new plants, mark plants as sold out, and update or delete plants. The app communicates with an API to persist data and allows for various CRUD (Create, Read, Update, Delete) operations.

## Core Features

- View all plants when the app starts
- Add a new plant to the page by submitting a form
- Mark a plant as "sold out"
- Search for plants by their name and see a filtered list of plants

## Advanced Features

- Update the price of a plant and persist the updated price after refreshing the page
- Delete a plant and persist the deletion after refreshing the page

## Endpoints

### Core Deliverables

#### GET `/plants`
Retrieves a list of all plants.

**Example Response:**
```json
[
  {
    "id": 1,
    "name": "Aloe",
    "image": "./images/aloe.jpg",
    "price": 15.99
  },
  {
    "id": 2,
    "name": "ZZ Plant",
    "image": "./images/zz-plant.jpg",
    "price": 25.98
  }
]
