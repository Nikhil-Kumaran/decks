---
# try also 'default' to start simple
theme: geist
# random image from a curated Unsplash collection by Anthony
# apply any windi css classes to the current slide
# class: "text-center"
# show line numbers in code blocks
lineNumbers: true
# some information about the slides, markdown enabled
info: |
  ## TypeScript advanced concepts
  Presentation slides for developers.
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
---

# Welcome to Slidev

Presentation slides for developers

---

# What is Slidev?

Slidev is a slides maker and presenter designed for developers, consist of the following features

- 📝 **Text-based** - focus on the content with Markdown, and then style them later
- 🎨 **Themable** - theme can be shared and used with npm packages
- 🧑‍💻 **Developer Friendly** - code highlighting, live coding with autocompletion
- 🤹 **Interactive** - embedding Vue components to enhance your expressions
- 🎥 **Recording** - built-in recording and camera view
- 📤 **Portable** - export into PDF, PNGs, or even a hostable SPA
- 🛠 **Hackable** - anything possible on a webpage

Read more about [Why Slidev?](https://sli.dev/guide/why)

---

# Code

Use code snippets and get the highlighting directly![^1]

```ts {all|2|1-6|9|all}
interface User {
  id: number;
  firstName: string;
  lastName: string;
  role: string;
}

function updateUser(id: number, update: User) {
  const user = getUser(id);
  const newUser = { ...user, ...update };
  saveUser(id, newUser);
}
```

---

# The End

---
