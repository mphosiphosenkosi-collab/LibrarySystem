# 📚 Library Borrowing System

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

**Developer:** Sipho Senkosi  
**Project:** Day 2 Challenge - Collections, LINQ & Business Logic  
**Course:** C# Extra Credit Challenges

## 🎯 Project Overview

A console-based Library Borrowing System that demonstrates:

- **Domain-Driven Design** with proper separation of concerns
- **Business Logic** using C# Collections and LINQ
- **Real-world modeling** of books, members, and borrowing transactions
- **Professional architecture** with clean, maintainable code

## 🏗️ Architecture

LibrarySystem/
├── Domain/ # Core business entities
│ ├── Models/ # Book, Member, BorrowRecord
│ ├── Enums/ # BookStatus, MemberStatus
│ └── Interfaces/ # Future abstraction layer
├── Services/ # Business logic and rules
├── Data/ # Repository pattern
└── Program.cs # Thin UI layer

text

## ✨ Features

- ✅ Book borrowing with business rules
- ✅ Member management with status tracking
- ✅ Borrowing history with LINQ queries
- ✅ Search functionality across books
- ✅ Input validation and error handling
- ✅ Professional project structure

## 🚀 Getting Started

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download)
- Git (for cloning)

### Installation

```bash
# Clone the repository
git clone https://github.com/YourUsername/LibrarySystem.git
cd LibrarySystem

# Build the project
dotnet build

# Run the application
cd LibrarySystem
dotnet run
📖 Usage Examples
csharp
// Borrow a book
library.BorrowBook(bookId: 1, memberId: 1);

// Search for books
var results = library.SearchBooks("C#");

// Get borrowing history
var history = library.GetMemberBorrowHistory(memberId: 1);
🧪 Testing
bash
# Run unit tests
cd LibrarySystem.Tests
dotnet test
🎓 Learning Outcomes
This project demonstrates:

Domain Modeling - Creating realistic business entities

LINQ Mastery - Using queries for business logic

Encapsulation - Protecting data integrity

Separation of Concerns - Clean architecture

Professional Practices - Git, documentation, testing

🔧 Technical Implementation
Key Design Patterns
Repository Pattern for data abstraction

Service Layer for business logic

Immutable Records for transaction history

Interface Segregation for testability

Business Rules Implemented
Members can borrow up to 5 books

Only available books can be borrowed

Suspended members cannot borrow

Books can be reserved when borrowed

📊 Sample Data
The system includes sample data:

5 technical books (C#, Java, Programming)

3 library members

Pre-configured borrowing scenarios

🤝 Contributing
Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

📝 License
This project is created for educational purposes as part of C# learning challenges.

👨‍💻 Author
SiphoSenkosi

GitHub: @mphosipho-collab

Email: siphosenkosi17@outlook

"Good code is its own best documentation." - Steve McConnell
