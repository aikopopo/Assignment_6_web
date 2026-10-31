# Assignment #6. jQuery (Selectors, Effects, Animations)

**Student:** Your Full Name
**Group:** Your Group

**Live demo:** https://your-username.github.io/your-repository/

## Description

A multi-page website that demonstrates the basics of jQuery: selectors, effects, DOM manipulation, animations and a mini project. Every task is on its own page, and all pages share the same navigation bar (Bootstrap navbar) that links to Task 0 – Task 11.

## Technologies

- HTML5
- CSS3 and Bootstrap 5.3.3 (CDN)
- JavaScript and jQuery 3.7.1 (CDN)

## Project structure

```
├── index.html     # Task 0. Setup
├── task1.html     # Task 1. Selectors & CSS
├── task2.html     # Task 2. Visibility Methods
├── task3.html     # Task 3. Fade Methods
├── task4.html     # Task 4. Slide Methods
├── task5.html     # Task 5. Add & Remove Elements
├── task6.html     # Task 6. Modifying Attributes
├── task7.html     # Task 7. Form Interaction
├── task8.html     # Task 8. Basic Animation
├── task9.html     # Task 9. Sequential Animations
├── task10.html    # Task 10. Combined Animation
├── task11.html    # Task 11. Mini Project: Bouncing Ball
├── images/        # images used in Task 3 and Task 6
└── README.md
```

## Tasks

| Page | Task | What it shows | Main jQuery methods |
|---|---|---|---|
| `index.html` | Task 0. Setup | jQuery from CDN, document ready, message in the console | `$(document).ready()`, `console.log()` |
| `task1.html` | Task 1. Selectors & CSS | Selecting by ID, class and tag; changing content and styles | `$("#id")`, `$(".class")`, `$("tag")`, `.text()`, `.html()`, `.css()` |
| `task2.html` | Task 2. Visibility Methods | Hide, show and toggle a paragraph | `.hide()`, `.show()`, `.toggle()` |
| `task3.html` | Task 3. Fade Methods | Fading an image | `.fadeIn()`, `.fadeOut()`, `.fadeToggle()` |
| `task4.html` | Task 4. Slide Methods | Collapsible panel | `.slideUp()`, `.slideDown()`, `.slideToggle()` |
| `task5.html` | Task 5. Add & Remove Elements | Adding items to the start/end of a list and removing the last one | `.append()`, `.prepend()`, `.remove()` |
| `task6.html` | Task 6. Modifying Attributes | Changing the `src` of an image and the `href` of a link | `.attr()` |
| `task7.html` | Task 7. Form Interaction | Name and Email inputs are displayed live below the form | `.on("input")`, `.val()`, `.text()`, `.focus()`, `.blur()` |
| `task8.html` | Task 8. Basic Animation | A square grows and moves | `.animate()` |
| `task9.html` | Task 9. Sequential Animations | Move right → move down → shrink → return to original | chained `.animate()` (animation queue) |
| `task10.html` | Task 10. Combined Animation | Opacity, size and position changed in one call | one `.animate()` with several properties |
| `task11.html` | Task 11. Mini Project | **Bouncing Ball** that moves across the scene and bounces back | `.animate()`, callback, `.stop(true)` |

## Mini project: Bouncing Ball

The ball moves across the scene in four steps (right-down, right-up, left-down, left-up). The last `.animate()` receives the `bounce` function as a callback, so the animation repeats until the **Stop** button is pressed (`.stop(true)` clears the animation queue).

