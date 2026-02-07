<h1 align="center">🦁 Literary Lions Forum</h1>

**[View Live Project Details](https://sureshpun.github.io/portfolio/projects/literary-lions-forum.html)**

**Literary Lions Forum** is a modern, high-performance discussion platform built from scratch with **Go** and **SQLite**. It offers a clean, responsive interface for users to engage in meaningful discussions, featuring custom authentication and a dynamic engagement system.

## 🌟Key Features

- **🔐 Custom Authentication**: Secure registration and login with session management.
- **📝 Full CRUD**: Create, read, update, and delete posts seamlessly.
- **💬 Engagement**: Threaded comments and interactivity (Likes/Dislikes).
- **📂 Categorization**: Filter content by topics like Movies, Books, and Games.
- **👤 User Profiles**: Customizable profiles with activity tracking.

## ✨Usage

**Register:** Create a new account with email, username, and password.

**Log in:** Access the forum using your credentials.

**Create posts:** Share your thoughts and literary insights.

**Comment & react:** Participate in discussions by commenting and liking posts or comments.
The interface is designed with simplicity and clarity, ensuring an intuitive user experience.

## 🛠️ Core Tech Stack

- **Language**: Go (Golang) 1.24+ - High performance and type safety.
- **Database**: SQLite - Serverless, transactional SQL.
- **Frontend**: Go Templates (SSR) & Vanilla CSS.
- **Infrastructure**: Docker & Docker Compose.

## 🌐 Web Visualization

```mermaid
flowchart TD
    subgraph Frontend [Presentation Layer]
        UI[HTML Templates]
        Style[Vanilla CSS]
    end

    subgraph Backend [Application Core]
        Handler[HTTP Handlers]
        Service[Business Logic]
        Auth[Custom Auth System]
    end

    subgraph Database [Data Persistence]
        SQLite[(SQLite DB)]
        Schema[Normalized Tables]
    end

    User((User)) -->|HTTP Requests| Handler
    Handler -->|Render| UI
    Handler -->|Validate| Service
    Service -->|Verify| Auth
    Service -->|Query/Exec| SQLite

    %% Connect definition nodes
    UI -.- Style
    SQLite -.- Schema

    style Frontend fill:#e1f5fe,stroke:#01579b
    style Backend fill:#fff3e0,stroke:#ff6f00
    style Database fill:#e8f5e9,stroke:#2e7d32
```

## 📺 Project Preview

[![Literary Lions Forum](../pic/literary-lions.png)](https://www.youtube.com/watch?v=sQkgPZ9ZreA&t=9s)

[← Back to Profile](../README.md)
