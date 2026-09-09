<div align="center">
    <p align="center">
        <a href="https://github.com/cybersecurity-dev/awesome-c-programming-language">
          <img width="8%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/C_logo.svg" />
        </a>
    </p>

# **`Awesome`** [C](https://github.com/cybersecurity-dev/awesome-c-programming-language) [Programming](https://github.com/cybersecurity-dev/C-Toolkit) Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[**`ANSI C`**](https://wikipedia.org/wiki/ANSI_C) | [**`C99`**](https://wikipedia.org/wiki/C99) | [**`C11`**](https://wikipedia.org/wiki/C11_(C_standard_revision)) | [**`C17`**](https://wikipedia.org/wiki/C17_(C_standard_revision)) | [**`C23`**](https://wikipedia.org/wiki/C23_(C_standard_revision))
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/C_Programming/new/)

```mermaid
flowchart TD

A[C Standard Library]

A --> B[stdio.h]
A --> C[stdlib.h]
A --> D[string.h]
A --> E[math.h]
A --> F[time.h]
A --> G[ctype.h]
A --> H[signal.h]

B --> B1[printf]
B --> B2[scanf]
B --> B3[fopen]

C --> C1[malloc]
C --> C2[free]
C --> C3[qsort]

D --> D1[strcpy]
D --> D2[strlen]
D --> D3[strcmp]

E --> E1[sin]
E --> E2[cos]
E --> E3[sqrt]
```

## 📖 Contents
- [Books](#books)
- [Blogs](#blogs)
- [Videos](#videos)
- [Reference](#reference)
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)

## Books
* [C Programming Language](https://www.amazon.com/Programming-Language-2nd-Brian-Kernighan/dp/0131103628)
* [C Programming Absolute Beginner's Guide](https://www.amazon.com/Programming-Absolute-Beginners-Guide-3rd/dp/0789751984)
* [C Programming: A Modern Approach](https://www.amazon.com/C-Programming-Modern-Approach-2nd/dp/0393979504)
* [Effective C : An Introduction to Professional C Programming](https://www.amazon.com/Effective-2nd-Introduction-Professional-Programming/dp/1718504128/)
* [Practical C Programming: Why Does 2+2 = 5986? (Nutshell Handbooks)](https://www.amazon.com/Practical-Programming-Does-Nutshell-Handbooks/dp/1565923065/)
* [C Pocket Reference](https://www.amazon.com/C-Pocket-Reference-Peter-Prinz/dp/0596004362/)
* [Expert C Programming: Deep Secrets](https://www.amazon.com/Expert-C-Programming-Deep-Secrets-ebook/dp/B00E0LASCU/)

## Blogs

## Videos
- [CS50x 2024 - Lecture 1 - C](https://youtu.be/cwtpLIWylAw?si=5HN_Ob8_fS3AtR4d)
- [How I program C by `Eskil Steenberg`](https://youtu.be/443UNeGrFoM?si=-Ryo1qd9Tf_cFJ3P)
- [Tips for C Programming by `Nic Barker`](https://youtu.be/9UIIMBqq1D4?si=zEWJlIhn_5VoOmAG)
- [extern c: Talking to C Programmers about C++ by `Dan Saks`](https://youtu.be/D7Sd8A6_fYU?si=SsoOOWUhv723hGpj)
- [C is So Back: Unbreaking the Charter by `Björkus Dorkus`](https://youtu.be/zLyz4kJvkvQ?si=o2759zzmUc0quVnr)
- [Advice for Writing Small Programs in C by `Sean Barrett`](https://youtu.be/eAhWIO1Ra6M?si=BybQtPH_LWy-_TSI)
- [Programming in Modern C with a Sneak Peek into C23 by `Dawid Zalewski`](https://youtu.be/lLv1s7rKeCM?si=FXLzWT0EZqfcj3z0)
- [Modern C and What We Can Learn From It by `Luca Sas`](https://youtu.be/QpAhX-gsHMs?si=Yws-mvslLTkwJBsv)

### Value Categories


### Security

```mermaid
flowchart TD

A[C Security]

A --> B[Memory Layout]

B --> C[Buffers]

C --> D[Stack]

C --> E[Heap]

D --> F[Buffer Overflow Concepts]

E --> G[Heap Corruption Concepts]

F --> H[Mitigations]

G --> H

H --> I[ASLR]

H --> J[DEP NX]

H --> K[Stack Canaries]

H --> L[Secure Coding]

L --> M[Code Review]

M --> N[Static Analysis]

N --> O[Fuzz Testing]

style A fill:#e74c3c,color:#fff
style H fill:#3498db,color:#fff
style O fill:#2ecc71,color:#fff
```

### Memory

```mermaid
flowchart TD

A[Process Memory]

A --> B[Text Segment]
A --> C[Data Segment]
A --> D[BSS Segment]
A --> E[Heap]
A --> F[Stack]

B --> B1[Executable Code]

C --> C1[Initialized Globals]

D --> D1[Uninitialized Globals]

E --> E1[Dynamic Allocation]

F --> F1[Local Variables]

style B fill:#3498db,color:#fff
style C fill:#2ecc71,color:#fff
style D fill:#f1c40f,color:#000
style E fill:#e74c3c,color:#fff
style F fill:#9b59b6,color:#fff
```
- [Understanding the C runtime memory model](https://youtu.be/3F3lp_F2YpQ?si=uM2zf6Sg5GcoPKoH)

## Reference


##

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-c-programming-resources/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-c-programming-resources-)
