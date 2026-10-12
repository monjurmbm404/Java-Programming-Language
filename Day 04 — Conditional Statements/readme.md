# 💻 Java Programming – Day 04: Conditional Statements

Welcome to **Day 04 of Java Programming**! 🎉
Today, we will learn how to **make decisions in Java**. Conditional statements allow your program to **execute different code based on conditions**. This is how your program can **think and react** like humans do.

---

## 🧩 What You’ll Learn Today

1. `if` Statement
2. `if-else` Statement
3. Nested `if`
4. `else-if` Ladder
5. `switch` Statement
6. Decision Making Programs

---

## 1️⃣ `if` Statement

The `if` statement executes a block of code **only if a condition is true**.

```java
int number = 10;

if (number > 0) {
    System.out.println(number + " is positive");
}
```

💡 If the condition is false, the code inside `if` **will not run**.

---

## 2️⃣ `if-else` Statement

The `if-else` statement allows your program to choose **between two paths**.

```java
int number = -5;

if (number >= 0) {
    System.out.println(number + " is non-negative");
} else {
    System.out.println(number + " is negative");
}
```

✅ One block executes if true, another if false.

---

## 3️⃣ Nested `if`

You can put an `if` inside another `if` to **check multiple conditions**.

```java
int number = 75;

if (number > 0) {
    System.out.println("Number is positive");

    if (number % 2 == 0) {
        System.out.println("Number is even");
    } else {
        System.out.println("Number is odd");
    }

} else {
    System.out.println("Number is zero or negative");
}
```

💡 Useful when you need **detailed decisions**.

---

## 4️⃣ `else-if` Ladder

Used to **check multiple conditions in sequence**.

```java
int marks = 85;

if (marks >= 90) {
    System.out.println("Grade: A+");
} else if (marks >= 75) {
    System.out.println("Grade: A");
} else if (marks >= 60) {
    System.out.println("Grade: B");
} else if (marks >= 50) {
    System.out.println("Grade: C");
} else {
    System.out.println("Grade: F");
}
```

💡 Checks **conditions from top to bottom**, stops at the first true condition.

---

## 5️⃣ `switch` Statement

The `switch` statement is useful when **one variable is compared with many values**.

```java
int day = 3;

switch (day) {
    case 1: System.out.println("Monday"); break;
    case 2: System.out.println("Tuesday"); break;
    case 3: System.out.println("Wednesday"); break;
    case 4: System.out.println("Thursday"); break;
    case 5: System.out.println("Friday"); break;
    case 6: System.out.println("Saturday"); break;
    case 7: System.out.println("Sunday"); break;
    default: System.out.println("Invalid Day");
}
```

✅ Often more **readable than multiple if-else statements**.

---

## 6️⃣ Decision Making Programs

Programs can **decide actions based on conditions**.

```java
int age = 18;

// Using if-else
if (age >= 18) {
    System.out.println("Eligible to vote");
} else {
    System.out.println("Not eligible to vote");
}

// Using ternary operator
String eligibility = (age >= 18) ? "Can Vote" : "Cannot Vote";
System.out.println(eligibility);
```

💡 Ternary operator is a **quick way to make decisions** in one line.

---

## ✅ Day 04 Summary

Today you learned:

- `if` Statement – run code only if condition is true
- `if-else` Statement – choose between two paths
- Nested `if` – check multiple conditions inside another
- `else-if` Ladder – check multiple conditions sequentially
- `switch` Statement – compare one variable with many values
- Decision Making Programs – practical examples using conditions

🎯 You are now ready for **Day 05**, where we will explore **Loops in Java**!

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


