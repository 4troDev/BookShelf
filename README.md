![Bookshelf Logo](Book_shelf-banner.png)

# Bookshelf

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub Issues](https://img.shields.io/github/issues/4troDev/bookshelf.svg)](https://github.com/4troDev/bookshelf/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/4troDev/bookshelf.svg)](https://github.com/y4troDev/bookshelf/pulls)
[![Contributors](https://img.shields.io/github/contributors/4troDev/bookshelf.svg)](https://github.com/4troDev/BookShelf/graphs/contributors)

Bookshelf is an open-source project that aims to create a collaborative repository of recommended books. It allows users to share their favorite books and provide a brief description of each book. This project encourages a community-driven approach to discovering and exploring diverse literary works.

---

## Book Categories

To browse books by category, visit the [Categories](categories.md) page.

---

# Contributing

To contribute to Bookshelf, follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Add a new `.json` file under the book's name in the following format:

```json
{
  "title": "Book Title",
  "author": "Author Name",
  "category": "Book Category",
  "summary": "Brief summary or description of the book.",
  "rating": 4,
  "buy_link": "https://example.com/book",
  "User": "Person who requested to add the book, to credit their contribution"
}
```

4. Fill in the details for the book you want to add. Make sure to follow the format above and add the `.json` file to the `books-info` folder.

5. Add the book under the appropriate category in the `books` folder in the following format:

```markdown
[Book Title](https://book.com/buy) by [Author Name](https://domain.com/author) - Brief summary or description of the book. (Rating: 0/5) 
```

6. Submit a pull request, including a clear description of the book you're adding.

7. Create an issue mentioning the book you added, so that we can add it to the appropriate category.
(eg: "Added 'Book Title' to the 'Book Category' category.")

Please ensure that the book information you provide is accurate and follows the structure outlined above.

---

## Guidelines

- Only add books that you have personally read and recommend to others.
- Ensure that the book information you provide is complete and accurate.
- Respect the work of others and make sure to credit the original contributors.
- Be mindful of the book categories to ensure a diverse representation of genres.

---

## Book Information

Each book entry should include the following information:

- **Title**: The title of the book.
- **Author**: The name of the book's author.
- **Category**: The category or genre to which the book belongs.
- **Summary**: A brief summary or description of the book.
- **Rating**: A rating (1-5) representing your personal opinion of the book.
- **Buy Link**: A link to where the book can be purchased online.
- **User**: Your username or name to credit your contribution.

---

## License

Bookshelf is released under the [MIT License](LICENSE). By contributing to this project, you agree to make your contributions available under this license.

## Community

Join the Bookshelf community to engage with other book lovers, discuss recommendations, and contribute to the project. We welcome suggestions and improvements to make this repository a valuable resource for all readers.

We look forward to your contributions to Bookshelf! Happy reading and sharing! 📚