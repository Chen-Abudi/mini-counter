# mini-counter

## 📣 Overview:

- Intro
- Tech Stack
- Techniques
- Additional Link

## 🔎 Intro:

This is a practice project in React which displays a mini counter. The main focus on behind the scenes of react along optimization techniques.

## 🧰 Tech Stack:

- React
- JavaScript
- CSS3
- Vite

## 🛠️ Techniques:

- **_React APIs_**:
  - **`Memo`**: React memo checks for changes between the previous and current values for a given prop passed to the component. The default function carries out a shallow comparison on each passed in prop. It then checks for equality of incoming values with the existing values.
    - **`Note`**: **Don't overuse memo()!**
      - **Use it `as high up in the component tree as possible`ß**:
        Blocking a component execution there will also block all child component executions.
      - **Checking props with memo() `costs performance!`**: Don't wrap it around all your components - it will add a lot of unnecessary checks.
      - **`Do Not` use it on components where `props will change frequently`**: memo() would just perform a meaningless check in such cases (which costs performance).

---

---

## 🔗 Additional Link:

If you want to strengthen your knowledge and skills of **React, Redux, and more...** along **Best Practices**, Feel free to check this course on Udemy by **`Maximilian Schwarzmüller`**:

## Visit the Course [&#128073;&#127997; **HERE !**](https://www.udemy.com/course/react-the-complete-guide-incl-redux/)

**_`Shoutout to Maximilian Schwarzmüller for this project and its design, the lectures, the exercises, and the React course in Udemy. Mahalo, Thank you!`_** 🌺
