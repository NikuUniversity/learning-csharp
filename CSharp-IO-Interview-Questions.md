# Niku University

# C# I/O (Input/Output) Interview Questions 📂

A curated list of interview questions covering C# File I/O, Streams, and the `System.IO` namespace — from basics to advanced. Great for interview prep, self-study, or building a quiz app.

## 📌 Categories Covered

| Category | Question Range |
|----------|-----------------|
| I/O Basics & `System.IO` Namespace | 1–8 |
| File & Directory Operations | 9–20 |
| Streams | 21–32 |
| Readers & Writers | 33–44 |
| Binary & Memory I/O | 45–52 |
| Asynchronous I/O | 53–60 |
| Serialization | 61–68 |
| Exception Handling & Best Practices | 69–75 |

## 📋 Questions

| # | Question | Difficulty |
|---|----------|------------|
| 1 | What is the `System.IO` namespace used for in C#? | Beginner |
| 2 | What is the difference between synchronous and asynchronous I/O? | Intermediate |
| 3 | What is a stream in C#? | Beginner |
| 4 | What is the base class for all streams in C#? | Beginner |
| 5 | What is the difference between byte-based and character-based I/O? | Intermediate |
| 6 | What is buffering, and why is it used in I/O operations? | Intermediate |
| 7 | What is the difference between blocking and non-blocking I/O? | Advanced |
| 8 | Why is it important to always close or dispose of I/O resources? | Beginner |
| 9 | How do you check if a file exists in C#? | Beginner |
| 10 | How do you create a new file using `File` class? | Beginner |
| 11 | What is the difference between `File.Create` and `File.CreateText`? | Intermediate |
| 12 | How do you read all text from a file in one line of code? | Beginner |
| 13 | How do you write text to a file, overwriting existing content? | Beginner |
| 14 | How do you append text to an existing file? | Beginner |
| 15 | What is the difference between `File` and `FileInfo` classes? | Intermediate |
| 16 | What is the difference between `Directory` and `DirectoryInfo` classes? | Intermediate |
| 17 | How do you get a list of all files in a directory? | Beginner |
| 18 | How do you copy, move, and delete a file in C#? | Beginner |
| 19 | How do you recursively search for files in subdirectories? | Intermediate |
| 20 | What is the `Path` class used for, and why should you use it instead of string concatenation for file paths? | Intermediate |
| 21 | What is `FileStream`, and when would you use it? | Intermediate |
| 22 | What is the difference between `FileStream` and `MemoryStream`? | Intermediate |
| 23 | What are `FileMode`, `FileAccess`, and `FileShare` enums used for? | Intermediate |
| 24 | What is the difference between `FileMode.Create` and `FileMode.CreateNew`? | Intermediate |
| 25 | What is the purpose of `Stream.Flush()`? | Intermediate |
| 26 | What is the difference between `Stream.Read()` and `Stream.ReadAsync()`? | Intermediate |
| 27 | What is a `BufferedStream`, and what problem does it solve? | Advanced |
| 28 | What is the difference between `CanRead`, `CanWrite`, and `CanSeek` properties of a stream? | Intermediate |
| 29 | What does the `Seek()` method do on a stream? | Intermediate |
| 30 | What is the purpose of `using` statements when working with streams? | Beginner |
| 31 | What happens if you don't dispose of a `FileStream` object properly? | Intermediate |
| 32 | What is a `NetworkStream`, and how does it differ from a `FileStream`? | Advanced |
| 33 | What is the difference between `StreamReader` and `StreamWriter`? | Beginner |
| 34 | How do you read a file line by line using `StreamReader`? | Beginner |
| 35 | What is the purpose of the `Encoding` parameter in `StreamReader`/`StreamWriter`? | Intermediate |
| 36 | What is the difference between `StreamReader.ReadLine()` and `StreamReader.ReadToEnd()`? | Beginner |
| 37 | What is `TextReader` and `TextWriter`, and how do they relate to `StreamReader`/`StreamWriter`? | Intermediate |
| 38 | What is `StringReader` and `StringWriter`, and when would you use them? | Intermediate |
| 39 | How do you write formatted text to a file using `StreamWriter`? | Beginner |
| 40 | What is the `AutoFlush` property on `StreamWriter`? | Intermediate |
| 41 | What happens if you try to read past the end of a file? | Intermediate |
| 42 | How do you read a specific number of characters from a `StreamReader`? | Intermediate |
| 43 | Can `StreamReader` detect the encoding of a file automatically? | Advanced |
| 44 | What is the difference between `File.ReadAllLines()` and using `StreamReader` in a loop? | Intermediate |
| 45 | What is `BinaryReader` and `BinaryWriter` used for? | Intermediate |
| 46 | When would you choose binary I/O over text-based I/O? | Intermediate |
| 47 | What is `MemoryStream`, and what are common use cases for it? | Intermediate |
| 48 | How do you convert a `byte[]` array to a `MemoryStream` and back? | Intermediate |
| 49 | What is the difference between reading a file into memory versus streaming it? | Advanced |
| 50 | What are the performance implications of loading a large file entirely into memory? | Advanced |
| 51 | How do you copy data from one stream to another? | Intermediate |
| 52 | What is `Stream.CopyTo()`, and how does it simplify stream copying? | Intermediate |
| 53 | Why should file I/O operations be performed asynchronously in a UI or web application? | Intermediate |
| 54 | What is the difference between `File.ReadAllTextAsync()` and `File.ReadAllText()`? | Beginner |
| 55 | How do you write to a file asynchronously using `StreamWriter`? | Intermediate |
| 56 | What is the purpose of `async` and `await` in I/O operations? | Intermediate |
| 57 | What happens if you block on an async I/O call using `.Result` or `.Wait()`? | Advanced |
| 58 | How do you cancel an ongoing asynchronous file operation using `CancellationToken`? | Advanced |
| 59 | What is the difference between `Task`-based async I/O and the older `BeginRead`/`EndRead` APIs? | Advanced |
| 60 | What are common pitfalls when mixing synchronous and asynchronous I/O code? | Advanced |
| 61 | What is serialization, and why is it used with I/O in C#? | Beginner |
| 62 | What is the difference between binary serialization and JSON serialization? | Intermediate |
| 63 | How do you serialize an object to a file using `System.Text.Json`? | Intermediate |
| 64 | What is the difference between `System.Text.Json` and `Newtonsoft.Json`? | Intermediate |
| 65 | How do you serialize and deserialize an object to/from XML in C#? | Intermediate |
| 66 | What attributes are commonly used to control JSON serialization behavior? | Intermediate |
| 67 | What are the security risks of binary deserialization, and why was `BinaryFormatter` deprecated? | Advanced |
| 68 | How would you serialize a large object graph efficiently without loading it all into memory? | Advanced |
| 69 | What is the difference between `IOException` and `UnauthorizedAccessException`? | Intermediate |
| 70 | How do you handle a `FileNotFoundException` gracefully? | Beginner |
| 71 | Why is it best practice to use `try-finally` or `using` blocks with file operations? | Beginner |
| 72 | What is a file lock, and how can it cause I/O exceptions? | Intermediate |
| 73 | How do you handle concurrent access to the same file from multiple threads or processes? | Advanced |
| 74 | What are best practices for handling large file uploads/downloads in a web application? | Advanced |
| 75 | How would you design a class to safely read and write to a shared log file? | Advanced |

## 💡 How to Use This

- Filter by the **Difficulty** column to match your interview prep level.
- Practice writing small programs for each topic — e.g., reading a file asynchronously, comparing `FileStream` vs `MemoryStream`, or serializing an object to JSON.
- Pay extra attention to resource disposal (`using` statements) and async/await patterns — these are common areas interviewers probe for real-world understanding.

## 🤝 Contributing

Found a great question that should be added? Feel free to open a PR or issue with your suggestion.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
