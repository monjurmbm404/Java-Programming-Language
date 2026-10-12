# 💻 Java Programming – Day 06: Pattern Printing & Logic Building

Welcome to **Day 06 of Java Programming**! 🎉
Today, we will focus on **Pattern Printing and Logic Building**.
Patterns help you **understand loops better, develop logical thinking, and prepare for programming problems**.

---

## 🧩 What You’ll Learn Today

1. Number Patterns
2. Star Patterns
3. Pyramid Patterns
4. Reverse Patterns
5. Nested Loop Logic

---

## 1️⃣ Number Patterns

Number patterns use loops to print **numbers in a structured way**.
They help understand **nested loops**.

```java id="np1"
for(int i = 1; i <= 3; i++) {
    for(int j = 1; j <= 3; j++) {
        System.out.print(j + " ");
    }
    System.out.println();
}
```

💡 Prints:

```
1 2 3
1 2 3
1 2 3
```

Another example — **incremental number triangle**:

```
1
1 2
1 2 3
```

---

## 2️⃣ Star Patterns

Star patterns use `*` to form shapes.
Great for **practicing nested loops**.

```java id="sp1"
// Right-angled triangle
for(int i = 1; i <= 4; i++) {
    for(int j = 1; j <= i; j++) {
        System.out.print("* ");
    }
    System.out.println();
}
```

💡 Output:

```
*
* *
* * *
* * * *
```

---

## 3️⃣ Pyramid Patterns

Pyramid patterns require **spacing** and careful **nested loop planning**.

```java id="pp1"
int rows = 4;
for(int i = 1; i <= rows; i++) {
    for(int j = rows; j > i; j--) { System.out.print(" "); }
    for(int k = 1; k <= (2*i - 1); k++) { System.out.print("*"); }
    System.out.println();
}
```

💡 Output:

```
   *
  ***
 *****
*******
```

---

## 4️⃣ Reverse Patterns

Reverse patterns **flip the structure**, useful for understanding loop control.

```java id="rp1"
// Reverse triangle
for(int i = 5; i >= 1; i--) {
    for(int j = 1; j <= i; j++) {
        System.out.print("* ");
    }
    System.out.println();
}
```

💡 Output:

```
* * * * *
* * * *
* * *
* *
*
```

---

## 5️⃣ Nested Loop Logic

Nested loops are not just for patterns — you can **build logic** like incrementing numbers or multiplication tables.

```java id="nl1"
// Increment numbers in rows
int num = 1;
for(int i = 1; i <= 3; i++) {
    for(int j = 1; j <= i; j++) {
        System.out.print(num + " ");
        num++;
    }
    System.out.println();
}
```

💡 Output:

```
1
2 3
4 5 6
```

Multiplication table logic using nested loops:

```
1 2 3
2 4 6
3 6 9
```

---

## ✅ Day 06 Summary

Today you learned:

- Number Patterns – print sequences of numbers
- Star Patterns – create shapes with `*`
- Pyramid Patterns – combine spacing and stars
- Reverse Patterns – flip patterns for logic practice
- Nested Loop Logic – build programs using nested loops

🎯 Pattern printing strengthens **logical thinking and problem-solving skills**.

---

This guide prepares you to handle **more complex programming exercises and coding challenges**!

---





# Author

## **Engr. Md Monjur Bakth Mazumder**

🎓 **Secondary School Certificate (SSC) from [Shah Helal High School](https://www.shahhelalhs.edu.bd/)**

🎓 **Diploma in Computer Science and Technology from [Moulvibazar Polytechnic Institute (MPI)](https://mpi.moulvibazar.gov.bd/)**

🎓 **BSc in Computer Science & Engineering (CSE)** _(Ongoing)_ **at [Sylhet International University (SIU)](https://siu.edu.bd/)**

---

## Support the Project

If you found this repository helpful, please consider giving it a **⭐ Star**. It helps others discover the project and motivates future development.

---


## Connect with Me

### Professional Profiles

| Platform | Link |
|:---|:---|
| Portfolio | [monjurmbm404.github.io](https://monjurmbm404.github.io) |
| GitHub | [monjurmbm404](https://github.com/monjurmbm404) |
| LinkedIn | [monjurmbm404](https://www.linkedin.com/in/monjurmbm404) |
| Medium | [@monjurmbm404](https://medium.com/@monjurmbm404) |

### Competitive Programming

| Platform | Link |
|:---|:---|
| Codeforces | [monjurmbm404](https://codeforces.com/profile/monjurmbm404) |
| CodeChef | [monjurmbm404](https://www.codechef.com/users/monjurmbm404) |
| LeetCode | [monjurmbm404](https://leetcode.com/u/monjurmbm404) |
| VJudge | [monjurmbm404](https://vjudge.net/user/monjurmbm404) |

### Social Media

| Platform | Link |
|:---|:---|
| Facebook | [monjurmbm404](https://www.facebook.com/monjurmbm404) |
| X (Twitter) | [@monjurmbm404](https://x.com/monjurmbm404) |
| YouTube | [@monjurmbm404](https://youtube.com/@monjurmbm404) |

### Contact Information

| Type | Email |
|:---|:---|
| Professional | [monjurmbm404@gmail.com](mailto:monjurmbm404@gmail.com) |

