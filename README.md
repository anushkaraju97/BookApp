# Book Search App

## Overview
The Book Search App is a Lightning Web Component (LWC) that allows users to search for books using the Google Books API. It dynamically fetches and displays book details based on user input, including the book title, cover image, published date, and average rating.

## Features
- Search for books by title using a search input field.
- Real-time API fetching with a delay to optimize network requests.
- Responsive design using Lightning Layout and SLDS styling.
- Displays book details such as the cover image, title, published date, and average rating.
- Initial book list shown based on the default query ("Man").

## How It Works
1. When the app loads, it fetches and displays books related to the default query ("Man").
2. Users can type a book title in the search bar, which triggers a debounced API request after 1 second.
3. The app retrieves the data from the Google Books API and updates the UI dynamically.
4. Each book is displayed inside a Lightning Card with its details neatly formatted.
