# KahaaniVerse Data

Repository for hosting book data and images for the KahaaniVerse Android app.

## File Structure
- `books.json`: Main catalog with metadata for all books.
- `latest.json`: List of the 10 most recently added books.
- `trending.json`: List of trending books.
- `categories.json`: Book IDs organized by genre.
- `books/`: Individual JSON files for each book containing full content.
- `covers/`: Cover images for all books.

## Setup Instructions

### 1. Enabling GitHub Pages
- Go to repository **Settings**.
- Navigate to **Pages** section.
- Select **Deploy from a branch**.
- Set **Branch** to `main` and folder to `/(root)`.
- Click **Save**.

### 2. Testing
- Wait 2-5 minutes for deployment.
- Access: `https://rishishpradhan16.github.io/kahaaniverse-data/books.json`

## Adding New Content
1. Create new book JSON in `books/[id].json`.
2. Add cover image to `covers/[id].jpg`.
3. Update `books.json`, `latest.json`, and `categories.json`.
4. Commit and push.

---
*Powered by KahaaniVerse*
