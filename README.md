# Challenge Day 25: Download Cover Images of the first 10 Books

Goal:

- Visit https://books.toscrape.com/
- Scrape the first 10 books listed on the homepage
- For each book, extract:
    - Title
    - Image URL

Then:

- Download each image
- Save it to a local `images/` folder with the filename as 
the book title (sanitized)

Example:

Title: "A Light in the Attic"
Saved as: image/A_light_in_the_Attic.png

Bonus:

- Handle invalid filename characters
- Show download progress