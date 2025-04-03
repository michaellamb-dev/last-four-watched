# Last Four Watched [![built with Codeium](https://codeium.com/badges/main)](https://codeium.com) 

A specialized web service that generates shareable "Last Four Watched" images from a user's Letterboxd profile. This project fetches a Letterboxd RSS feed, extracts the most recent four film entries, and creates a visually appealing image grid that can be easily shared on social media.

This project is designed to be interactive and user-friendly, allowing visitors to generate Last Four Watched images for any Letterboxd username without requiring API credentials. The proof-of-concept includes a fully interactive webpage for demonstration purposes.

Keep reading for more details.

## Architecture

Review this [sequence diagram](/sequence-diagram.md) to understand how Last Four Watched works. 

## Features

- Fetches the most recent four watched films from any Letterboxd profile
- Generates a shareable image grid of the last four watched films
- Interactive web interface for entering Letterboxd usernames
- High-quality film poster images in a consistent layout
- Mobile-friendly design for on-the-go image generation

## Usage

1. Visit the web interface and enter any Letterboxd username
2. The application will fetch the user's most recent four watched films
3. A shareable image grid will be generated automatically
4. Download or share the image directly to social media

## Development Setup

This project is currently a proof-of-concept without API credentials. To set up the development environment:

1. Clone this repository
2. Install the required dependencies
3. Run the local development server
4. Access the web interface to test the image generation functionality

The application simulates the RSS feed fetching process and demonstrates the user interface for the Last Four Watched image generator.

## Deployment

This project is set up for deployment on GitHub Pages. To deploy:

1. Fork this repository
2. Go to your repository settings > Secrets and variables > Actions
3. Add a new secret named `DISCORD_WEBHOOK_URL` with your Discord webhook URL (if using the contact feature)
4. Enable GitHub Pages in your repository settings
5. Push changes to the main branch to trigger deployment

The site will be automatically deployed to `https://[your-username].github.io/last-four-watched/`

## Future Enhancements

- Integration with Letterboxd API when credentials are available
- Customizable image layouts and templates
- Additional social sharing options
- User accounts to save favorite profiles
- Historical tracking of Last Four Watched changes

---

## Template Attribution

Multiverse by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)

Credits:

    Demo Images:
        Unsplash (unsplash.com)

    Icons:
        Font Awesome (fontawesome.io)

    Other:
        jQuery (jquery.com)
        Poptrox (github.com/ajlkn/jquery.poptrox)
        Responsive Tools (github.com/ajlkn/responsive-tools)
