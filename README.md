# Joke API Command Line Tool

This command line tool interacts with the "icanhazdadjoke" API to bring humor to your terminal.

## Features

- Search for jokes based on a specified search term.
- Save jokes to a file for future laughs.
- Explore the most popular joke in the leaderboard.

## Installation
1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/joke-api-cli.git
    cd joke-api-cli
    ```

2. Install dependencies:

    ``
    npm install
    ``
 ## Usage 

 ### Search for Jokes

To search for jokes, use the following command:

``
node joke-cli.js <searchTerm>
``

Replace <searchTerm> with your desired search term.

 ## Examples
1. Search for a Joke:

``
node joke-cli.js cats
``

This command searches for jokes related to "cats."

2. View Leaderboard:

``
node joke-cli.js leaderboard
``

This command displays the most popular joke saved in the leaderboard.
