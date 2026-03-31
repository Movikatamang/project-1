Project discription:
Key-Value Store Database


This project implements a simple command-line key-value database that supports persistent storage. The system allows users to store and retrieve data using basic commands, while ensuring that all data is saved to disk and remains consistent across program restarts.
- Supports basic operations:
  - SET <key> <value>
  - GET <key>
  - EXIT
- Persistent storage using append-only file (`data.db`)
- Data recovery by replaying logs on startup
