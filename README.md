# Tinder Swipe Cards

This is a simple implementation of Tinder-like swipe cards using HTML, CSS, and JavaScript. The project displays a set of profile cards that users can swipe left (reject) or right (like) using buttons or touch gestures. The project uses `hammer.js` for swipe gesture support and FontAwesome for icons.

## Table of Contents

- [Project Demo](#project-demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## Project Demo

![Demo Image](./images/demo.png)

## Features

- Swipe left or right on profile cards to either reject or like the profiles.
- Animated transition effects for smooth user interaction.
- Use buttons for 'like' and 'dislike' actions or swipe gestures for mobile-friendly interaction.
- Profiles are pre-loaded with images, names, and other basic information.
  
## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/tinder-swipe-cards.git
    ```

2. Navigate to the project directory:
    ```bash
    cd tinder-swipe-cards
    ```

3. Open `index.html` in your browser:
    ```bash
    open index.html
    ```

## Usage

Once the page is loaded, users will see a stack of profile cards. They can interact with the cards in the following ways:

- **Swipe left**: To reject a profile.
- **Swipe right**: To like a profile.
- **Buttons**: The "X" button rejects the profile, and the heart button likes the profile.

## Technologies Used

- **HTML5**: For the structure of the webpage.
- **CSS3**: For styling the webpage.
- **JavaScript**: For interaction and logic.
- **Hammer.js**: A JavaScript library for handling touch gestures on mobile devices.
- **FontAwesome**: For the icons used in buttons.
  
## Future Enhancements

- Dynamic data fetching to load profiles from a backend server.
- Add more detailed profiles with multiple images and extended information.
- Integrate with a backend service for saving likes and dislikes.
- Add animations for swiping left and right.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
