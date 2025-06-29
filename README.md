# Book-Rental
This Java program simulates a comic book rental system for 90s Comic Café. It allows customers to search for comics, rent books as members or non-members, and calculates rental fees with discounts. The system uses object-oriented principles and file handling for data processing.
# 📚 90s Comic Café - Book Rental System

This Java program simulates a comic book rental system for the **90s Comic Café**. It supports both member and non-member customers, allows book searching, handles rental transactions, and calculates rental fees with member discounts.

---

## 💡 Features

- 🔍 Search for comic book availability by title
- 🧾 Process comic rentals with customer details
- 🧑‍🤝‍🧑 Membership support:
  - Members receive 5% discount
  - Non-members pay full price
- 📁 Data saved to `member.txt` or `nonmember.txt`
- 📘 Comics categorized by **Red**, **Yellow**, or **Green**
- 💰 Fee calculated based on category and rental days

---

## 🧱 Technologies Used

- Java (Object-Oriented Programming)
- File I/O (`comic.txt`, `member.txt`, `nonmember.txt`)
- Polymorphism, Inheritance, Abstraction

---

## 📂 File Structure

BookRentalSystem/
├── Book.java
├── BookRental.java
├── Member.java
├── NonMember.java
├── BookApp.java
└── comic.txt (required input file)

---

## 🚀 How to Run

1. Compile all `.java` files:
```bash
javac *.java

2. Run the program:
java BookApp

3. Make sure comic.txt is in the same directory, formatted like:
5;Naruto,Bleach,OnePiece;Red

📄 Sample Output
Welcomeヾ(≧▽≦*)o
Do you want to search for a book or process rentals?
1 - Search for a book
2 - Process rentals

Enter comic title to search:
> Naruto
Book available

📌 Notes
Members enjoy 5% rental discounts
Invalid input will prompt user for corrections
Works best with clean and structured comic.txt data

FATIN QISTINA BINTI MOHD KAMARUL
Diploma in Computer Science - UiTM Jasin
Semester 2 Final Project
