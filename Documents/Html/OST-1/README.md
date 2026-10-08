# 🎂 Age Calculator – Java

A simple **Age Calculator** developed using Java. The program takes the user's date of birth as input and calculates their current age in **years, months, and days**.

## 📌 Features

- Takes date of birth from the user
- Calculates the current age automatically
- Displays age in:
  - Years
  - Months
  - Days
- Uses Java's built-in `LocalDate` and `Period` classes
- Simple and beginner-friendly Java project

## 🛠️ Technologies Used

- **Java**
- **Java 8+**
- `Scanner`
- `LocalDate`
- `Period`

## 📂 Project Structure

```text
AgeCalculator/
│
├── AgeCalculator.java
└── README.md
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/age-calculator.git
```

### 2. Open the Project

Open the project in any Java IDE such as:

- IntelliJ IDEA
- Eclipse
- VS Code

### 3. Compile the Program

```bash
javac AgeCalculator.java
```

### 4. Run the Program

```bash
java AgeCalculator
```

## 💻 Example

### Input

```text
Enter your birth year: 2003
Enter your birth month: 5
Enter your birth day: 15
```

### Output

```text
Your Age is:
23 Years 4 Months 23 Days
```

## 🧠 How It Works

The program uses Java's `LocalDate` class to represent the birth date and the current date.

```java
LocalDate birthDate = LocalDate.of(year, month, day);
LocalDate currentDate = LocalDate.now();
```

The `Period.between()` method calculates the difference between the two dates:

```java
Period age = Period.between(birthDate, currentDate);
```

The result is then displayed as years, months, and days.

## 📚 Learning Outcomes

This project helps beginners understand:

- Java input using `Scanner`
- Variables and data types
- Date and time API
- `LocalDate`
- `Period`
- Basic Java programming
- GitHub project documentation

## 🔮 Future Improvements

- Add a graphical user interface (GUI)
- Add date validation
- Calculate total days lived
- Add next birthday calculation
- Create a web version using HTML, CSS, and JavaScript

## 👨‍💻 Author

**Rohan Dadasaheb Jadhav**

Computer Science & Engineering Student

---

⭐ If you found this project useful, consider giving the repository a star!