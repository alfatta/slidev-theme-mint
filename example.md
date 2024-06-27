---
theme: ./
---

# Presentation Title

Presentation subtitle

---

# What is Slidev?

Slidev is a slide maker and presentation tool designed for developers. It includes the following features:

- 📝 **Text-based** - focus on your content with Markdown, then style it later
- 🎨 **Themable** - themes can be shared and reused as npm packages
- 🧑‍💻 **Developer Friendly** - code highlighting, live coding with autocompletion
- 🤹 **Interactive** - embed Vue components to enhance your expressions
- 🎥 **Recording** - built-in recording and camera view
- 📤 **Portable** - export to PDF, PPTX, PNGs, or even a hostable SPA
- 🛠 **Hackable** - virtually anything that's possible on a webpage is possible in Slidev

<br>
<br>

Read more about [Why Slidev?](https://sli.dev/guide/why)

---

# Navigation

Hover on the bottom-left corner to see the navigation's controls panel

## Keyboard Shortcuts

|     |     |
| --- | --- |
| <kbd>space</kbd> / <kbd>tab</kbd> / <kbd>right</kbd> | next animation or slide |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | previous animation or slide |
| <kbd>up</kbd> | previous slide |
| <kbd>down</kbd> | next slide |

---
layout: image-right
image: https://cover.sli.dev
---

# Layout `image-right`

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque consectetur porta velit, et ultricies lacus imperdiet vitae. Aenean posuere egestas nisl, at ullamcorper lorem facilisis ac.

Nullam tincidunt diam eget arcu consequat euismod. Donec rutrum neque tellus, et elementum nunc accumsan ac. Nullam tincidunt neque quis tortor laoreet, a convallis arcu gravida. Sed quis mauris nec mi placerat fermentum in et nulla. 

---
layout: image-left
image: https://cover.sli.dev
---

# Layout `image-left`

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque consectetur porta velit, et ultricies lacus imperdiet vitae. Aenean posuere egestas nisl, at ullamcorper lorem facilisis ac.

Nullam tincidunt diam eget arcu consequat euismod. Donec rutrum neque tellus, et elementum nunc accumsan ac. Nullam tincidunt neque quis tortor laoreet, a convallis arcu gravida. Sed quis mauris nec mi placerat fermentum in et nulla. 

---
layout: default-alt
---

# Layout `default-alt`

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque consectetur porta velit, et ultricies lacus imperdiet vitae. Aenean posuere egestas nisl, at ullamcorper lorem facilisis ac.

Nullam tincidunt diam eget arcu consequat euismod. Donec rutrum neque tellus, et elementum nunc accumsan ac. Nullam tincidunt neque quis tortor laoreet, a convallis arcu gravida. Sed quis mauris nec mi placerat fermentum in et nulla. 

---

# Code

Use code snippets and get the highlighting directly!

```ts
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: Partial<User>) {
  const user = getUser(id)
  const newUser = { ...user, ...update }
  saveUser(id, newUser)
}
```

---

# LaTeX

## Time evolution of a quantum state

The time evolution of a quantum state is described by the Schrödinger equation:

$$
{\displaystyle i\hbar {\frac {\partial }{\partial t}}\psi (t)=H\psi (t).}
$$

Here $𝐻$ denotes the [Hamiltonian](https://en.wikipedia.org/wiki/Hamiltonian_(quantum_mechanics)), the observable corresponding to the [total energy](https://en.wikipedia.org/wiki/Total_energy) of the system, and $ℏ$ is the reduced [Planck constant](https://en.wikipedia.org/wiki/Planck_constant). The constant 
$𝑖ℏ$ is introduced so that the Hamiltonian is reduced to the [classical Hamiltonian](https://en.wikipedia.org/wiki/Hamiltonian_mechanics) in cases where the quantum system can be approximated by a classical system; the ability to make such an approximation in certain limits is called the [correspondence principle](https://en.wikipedia.org/wiki/Correspondence_principle).

Source: Wikipedia [Quantum Mechanics](https://en.wikipedia.org/wiki/Quantum_mechanics#Time_evolution_of_a_quantum_state)

---
layout: end
---

# Thank You

Learn more on

[Documentation](https://sli.dev) / [GitHub Repo](https://github.com/slidevjs/slidev)
