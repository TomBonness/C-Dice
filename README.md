# 🎲 Dice Roller (C)

A simple terminal dice rolling simulator written in C. Rolls a 6-sided die 10 times, stores each result along with a timestamp, and displays the full roll history and average value.

---

## 🕹 How to Run

```bash
./roller
```

You’ll see a list of 25 dice rolls with timestamps and the calculated average at the end.

---

## 📦 Build It Yourself

```bash
gcc main.c -o roller
```

---

## 🌟 Bonus Features

- Timestamp for each roll using `ctime()`
- Newline removal using `strcspn()`
- Sleep delay between rolls (`sleep(1)` on POSIX systems)
- Average roll value computed and displayed

---
