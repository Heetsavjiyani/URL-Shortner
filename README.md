A lightweight Flask-based web service that converts long URLs into compact, redirectable Base62-encoded short links. It uses SQLite for persistent mapping storage.

🚀 Features
1.Shorten URLs: Transforms long URLs into human-readable Base62 codes.

2.Persistent Storage: Uses SQLite to store original URLs and their short codes.

3.Redirect Handling: Decodes the short link and forwards users to the original URL.

4.Minimal Dependencies: Built with Flask and standard Base62 encoding routines.

🛠️ Tech Stack
Python (3.x)

1.Flask – lightweight web framework

2.SQLite – file-based relational database

3.Custom Base62 encoder/decoder
