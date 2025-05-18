# Stone Paper Scissors

This project is a browser-based implementation of the classic "Rock-Paper-Scissors" game, stylized as **Stone-Paper-Scissors**, created as part of the Foundations course in [The Odin Project](https://www.theodinproject.com/) curriculum then further modified for hackathon. It serves as an introductory web development exercise focusing on core concepts such as HTML structure, CSS styling, JavaScript logic, DOM manipulation, and interactive design patterns.

## Overview

The game allows users to play rounds of Stone-Paper-Scissors against a computer opponent. The interface is visually styled with a custom background, responsive layout, and interactive elements that provide immediate feedback based on player choices. Each round displays the result, updates the score, and announces the winner once a certain score threshold is reached.

This project emphasizes best practices in beginner front-end development and is structured to be readable, scalable, and visually presentable.

## Features

- **Interactive Gameplay**: Users can click on stone, paper, or scissors to make a choice.
- **Computer Opponent**: The computer's choice is randomly generated each round.
- **Score Keeping**: Both the player's and the computer’s scores are tracked and displayed.
- **Game End Condition**: The game concludes when either side reaches a winning score, triggering a final result display.
- **Dynamic Interface**: The interface updates in real time without reloading the page.
- **Custom Background**: A background image adds visual appeal and thematic consistency.
- **Responsive Design**: Works across modern desktop and mobile browsers.

## Technologies Used

- **HTML5**: Defines the semantic structure of the interface.
- **CSS3**: Handles layout, positioning, and visual styling including background images.
- **Vanilla JavaScript (ES6+)**: Implements core game logic, DOM updates, and interaction handling.
- **Git & GitHub**: Version control and source code hosting.
- **Vercel** *(optional)*: Deployment platform for static front-end applications.

## Project Directory Structure

```
odin-stone_paper_scissors/
├── public/
│   ├── index.html         # Main HTML file containing the game structure
│   └── background.jpg     # Background image used in styling
├── .gitignore             # File specifying untracked files for Git
├── .vercel/               # Configuration directory for Vercel deployment
│   ├── README.txt
│   └── project.json
├── .git/                  # Git versioning metadata
└── README.md              # Project documentation (this file)
```

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

- A modern web browser such as Google Chrome, Firefox, Safari, or Edge.
- (Optional) A text editor like VS Code if you wish to inspect or modify the code.

### Installation and Local Use

1. **Clone the repository** (if hosted online):
   ```bash
   git clone https://github.com/Aktagh1234/odin-stone_paper_scissors.git
   cd odin-stone_paper_scissors
   ```

2. **Open the game in your browser**:
   Navigate to the `public/` folder and double-click `index.html`, or right-click and select *Open with...* your browser.

   Alternatively, you can serve the project locally using a simple HTTP server (e.g., Python):

   ```bash
   cd public
   python -m http.server 8000
   ```

   Then visit `http://localhost:8000` in your browser.

## Deployment

This project can be deployed easily on any static hosting platform such as GitHub Pages or Vercel.

### Deploying on Vercel

1. Visit [vercel.com](https://vercel.com) and sign in.
2. Import the GitHub repository.
3. Ensure the root directory is set correctly (the HTML entry point is under `public/`).
4. Click "Deploy" and wait for the build to complete.

### Deploying on GitHub Pages

1. Push the repository to GitHub.
2. Go to the repository’s Settings → Pages.
3. Choose the `main` branch and `/public` folder as the source.
4. Save and wait for GitHub Pages to generate the live link.

## Future Improvements

- Add animations for choice selection and result display
- Support for sound effects and background music
- Implement a restart/reset game button
- Track match history and allow score saving in `localStorage`
- Provide difficulty levels (e.g., smarter AI based on previous moves)

## Contributing

Contributions are welcome and appreciated. Please fork the repository and submit a pull request with a detailed explanation of your changes. For major changes or feature requests, consider opening an issue first to initiate discussion.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute it for personal and educational purposes.

## Author

Developed by Aashi Kushwaha as part of The Odin Project curriculum and further modified for hackathon. For inquiries or feedback, feel free to contact via GitHub.
