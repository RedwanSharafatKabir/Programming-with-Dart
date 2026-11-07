# Programming with Dart 🎯

> Learn the **Dart programming language** from scratch, then use it to build **Android & iOS apps with Flutter**.

![Dart](https://img.shields.io/badge/Language-Dart-0175C2?logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Framework-Flutter-02569B?logo=flutter&logoColor=white)
![Level](https://img.shields.io/badge/Level-Beginner-brightgreen)

---

## 📖 About This Repository

This repository is a hands-on guide for absolute beginners. It starts with the fundamentals of Dart (variables, functions, classes, and more) and prepares you for mobile app development with Flutter.

Every topic comes with small, runnable code examples so you learn by doing, not just by reading.

**Who is this for?**

- Complete beginners with no programming experience
- Students who want to start mobile app development
- Developers coming from Java, Kotlin, JavaScript, or C who want to pick up Dart quickly

---

- **`Dart Programming/`** contains the core Dart language examples. Start here.

---

## 🧰 Prerequisites

You only need:

- A computer (Windows, macOS, or Linux)
- A text editor or IDE
- Curiosity and a bit of patience 🙂

No prior coding knowledge is required.

---

## ⚙️ Setup Guide

### Option 1: Run Dart online (fastest, no install)

Open [DartPad](https://dartpad.dev) in your browser, paste any example from this repo, and click **Run**.

### Option 2: Install Dart on your computer

1. Download the Dart SDK from the official site: <https://dart.dev/get-dart>
2. Verify the installation:

   ```bash
   dart --version
   ```

3. Install an editor:
   - [VS Code](https://code.visualstudio.com/) with the **Dart** extension (recommended for beginners)
   - [Android Studio](https://developer.android.com/studio) / IntelliJ IDEA with the Dart plugin

### Option 3: Install Flutter (for building apps later)

Flutter already includes Dart. Follow the official guide: <https://docs.flutter.dev/get-started/install>

Then check your setup:

```bash
flutter doctor
```

---

## ▶️ How to Run the Code

1. **Clone this repository**

   ```bash
   git clone https://github.com/RedwanSharafatKabir/Programming-with-Dart.git
   cd Programming-with-Dart
   ```

2. **Go to the Dart lessons**

   ```bash
   cd "Dart Programming"
   ```

3. **Run any Dart file**

   ```bash
   dart run your_file_name.dart
   ```

   (Older Dart versions use `dart your_file_name.dart`.)

### Your first Dart program

```dart
void main() {
  print('Hello, Dart!');
}
```

Save it as `hello.dart` and run `dart run hello.dart`. You should see:

```
Hello, Dart!
```

---

## 🗺️ Learning Path

Follow the topics in this order. Each one builds on the previous.

| # | Topic | What You'll Learn |
|---|-------|-------------------|
| 1 | **Introduction & Hello World** | What Dart is, the `main()` function, `print()` |
| 2 | **Variables & Data Types** | `int`, `double`, `String`, `bool`, `var`, `final`, `const` |
| 3 | **Operators** | Arithmetic, comparison, logical, assignment |
| 4 | **Conditional Statements** | `if`, `else if`, `else`, `switch` |
| 5 | **Loops** | `for`, `while`, `do-while`, `break`, `continue` |
| 6 | **Functions** | Parameters, return values, optional & named parameters, arrow functions |
| 7 | **Collections** | `List`, `Set`, `Map` |
| 8 | **Null Safety** | Nullable types (`?`), `!`, `??`, `late` |
| 9 | **Object-Oriented Programming** | Classes, objects, constructors, inheritance, polymorphism, abstraction, encapsulation, mixins, interfaces |
| 10 | **Error Handling** | `try`, `catch`, `finally`, `throw` |
| 11 | **Asynchronous Programming** | `Future`, `async`/`await`, `Stream` |
| 12 | **Generics & Enums** | Reusable, type-safe code |
| 13 | **Intro to Flutter** | Widgets, layouts, and building your first Android & iOS app |

---

## 🧪 Quick Syntax Cheat Sheet

```dart
// Variables
String name = 'Dart';
int age = 10;
double price = 9.99;
bool isFun = true;
var city = 'Dhaka';        // type inferred
final year = 2025;         // set once at runtime
const pi = 3.1416;         // compile-time constant

// Function
int add(int a, int b) => a + b;

// List and Map
List<String> fruits = ['Apple', 'Banana', 'Mango'];
Map<String, int> marks = {'Math': 90, 'English': 85};

// Loop
for (var fruit in fruits) {
  print(fruit);
}

// Class
class Person {
  String name;
  int age;

  Person(this.name, this.age);

  void greet() => print('Hi, I am $name and I am $age years old.');
}

void main() {
  Person('Ayan', 22).greet();
}
```

---

## 💡 Tips for Beginners

- **Type the code yourself.** Don't just copy and paste. Typing builds muscle memory.
- **Change things and break them.** Modify examples and see what happens. Errors are great teachers.
- **Read error messages.** Dart's error messages are usually clear about what went wrong.
- **Practice daily.** Even 30 minutes a day beats a 5-hour session once a week.
- **Build small projects** (calculator, to-do list, number guessing game) after each major topic.

---

## 🏋️ Practice Ideas

- Write a program that checks whether a number is even or odd
- Print the multiplication table of any number
- Reverse a string
- Find the largest number in a list
- Build a simple bank-account class with deposit and withdraw methods
- Fetch fake data using `Future` and `async`/`await`

---

## 📚 Helpful Resources

- [Official Dart Documentation](https://dart.dev/guides)
- [Dart Language Tour](https://dart.dev/language)
- [DartPad (online editor)](https://dartpad.dev)
- [Flutter Documentation](https://docs.flutter.dev)
- [Flutter Codelabs](https://docs.flutter.dev/codelabs)
- [Effective Dart (style guide)](https://dart.dev/effective-dart)

---

## 🤝 Contributing

Contributions are welcome! To add examples, fix typos, or improve explanations:

1. Fork this repository
2. Create a branch: `git checkout -b feature/your-topic`
3. Commit your changes: `git commit -m "Add: your topic"`
4. Push the branch: `git push origin feature/your-topic`
5. Open a Pull Request

---

## 👨‍💻 Author

**Redwan Sharafat Kabir**
Mobile Application Developer · Android (Java/Kotlin) · Flutter (Dart)

- GitHub: [@RedwanSharafatKabir](https://github.com/RedwanSharafatKabir)

---

## ⭐ Support

If this repository helped you, please give it a **star** ⭐ and share it with other learners. Happy coding! 🚀
