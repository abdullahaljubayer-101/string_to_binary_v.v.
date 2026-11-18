# 🔢 String to Binary (and Vice Versa)

![Java](https://img.shields.io/badge/Language-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Type](https://img.shields.io/badge/Type-CLI-lightgrey?style=flat-square)

A small Java console app that turns text into 8-bit binary, and turns binary back into readable text. 🤖 ↔️ 🧑

I wrote the conversion logic by hand (no `Integer.toBinaryString`) to really understand how characters map to ASCII codes and bits.

---

## ✨ Features

- ➡️ **String → Binary**: every character becomes an 8-bit binary group
- ⬅️ **Binary → String**: paste space-separated binary and get the text back
- 🔁 Menu loop, so you can keep converting until you exit

## 🚀 Run it

```bash
cd "String to Binary/src"
javac *.java
java Main
```

### Example

```text
1 for String to Binary.
2 for Binary to String.
0 for Exit

Enter Your Choice: 1
Enter String: Hi
Binary: 01001000 01101001
```

> 💡 For **Binary → String**, end your input with a space (e.g. `01001000 01101001 `) so the last character is read too.

## 📁 Project structure

```text
String to Binary/src/
├── Main.java            # Menu and input handling
├── StringToBinary.java  # Text → binary
└── BinaryToString.java  # Binary → text
```

---

Made by **Abdullah Al Jubayer** · [GitHub](https://github.com/abdullahaljubayer-101) · [Portfolio](https://abdullahaljubayer.com)
