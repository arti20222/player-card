# Basketball Player Card Component

The Basketball Player Card component is a React component designed to display information about a basketball player, including their name, image, position, and statistics (stats).

## Getting Started

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Prerequisites

Make sure you have Node.js and npm installed on your local environment.

### Installation

1. Clone the repository to your local machine:

   

2. Navigate into the project directory:

   cd basketball-player-card
 

3. Install dependencies using npm:

   npm install

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### Usage

To use the **Basketball Player Card** component in your React application, import it and pass props as shown in your application:

import React from 'react';
import BasketballPlayerCard from './components/BasketballPlayerCard';

const App = () => {
  const player = {
    name: "LeBron James",
    image: "https://example.com/lebron.jpg",
    position: "Forward",
    stats: {
      pointsPerGame: 25.4,
      assistsPerGame: 7.1,
      reboundsPerGame: 10.5
    }
  };

  return (
    <div>
      <BasketballPlayerCard 
        name={player.name}
        image={player.image}
        position={player.position}
        stats={player.stats}
      />
    </div>
  );
};

export default App;


### Component Structure

The `BasketballPlayerCard` component includes:

- **Player Image**: Displayed at the top of the card.
- **Player Name and Position**: Below the image.
- **Player Statistics**: Displays points per game, assists per game, and rebounds per game in a simple, readable format.

### Styling

Customize the appearance of the card by modifying the `BasketballPlayerCard.css` file.

### Animations

The card includes CSS animations for a smooth loading effect and hover interactions.

### Learn More

- You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).
- To learn React, check out the [React documentation](https://reactjs.org/).

```
