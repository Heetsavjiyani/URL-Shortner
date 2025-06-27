A lightweight Flask-based web service that converts long URLs into compact, redirectable Base62-encoded short links. It uses SQLite for persistent mapping storage.

🚀 Features
Shorten URLs: Transforms long URLs into human-readable Base62 codes.

Persistent Storage: Uses SQLite to store original URLs and their short codes.

Redirect Handling: Decodes the short link and forwards users to the original URL.

Minimal Dependencies: Built with Flask and standard Base62 encoding routines.

🛠️ Tech Stack
Python (3.x)

Flask – lightweight web framework

SQLite – file-based relational database

Custom Base62 encoder/decoder
