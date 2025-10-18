# HNG Internship Profile Card Project - Stage 0

A responsive, accessible Profile Card page built with semantic HTML, CSS, and JavaScript. This project fulfills all requirements for the HNG Stage 0 task.

## 🚀 Live Demo

[View Live Demo](https://hng-fe-stage0.vercel.app/) - https://hng-fe-stage0.vercel.app/
## Features

**Semantic HTML**: Uses proper semantic elements (`<article>`, `<header>`, `<figure>`, `<nav>`, `<section>`)
-   **Accessibility**: Full keyboard navigation, ARIA labels, focus management
-   **Responsive Design**: Mobile-first approach with breakpoints for tablet and desktop
-   **Testable**: All elements include required `data-testid` attributes
-   **Dynamic Content**: Real-time display of current time in milliseconds
-   **Modern CSS**: Flexbox/Grid layouts with smooth animations

## Required Elements

| Element                     | data-testid                  | Status |
| --------------------------- | ---------------------------- | ------ |
| Profile card root container | `test-profile-card`          | ✅     |
| Name (plain text)           | `test-user-name`             | ✅     |
| Short biography (paragraph) | `test-user-bio`              | ✅     |
| Current time (milliseconds) | `test-user-time`             | ✅     |
| Avatar image                | `test-user-avatar`           | ✅     |
| Social links list           | `test-user-social-links`     | ✅     |
| Individual social links     | `test-user-social-{network}` | ✅     |
| Hobbies list                | `test-user-hobbies`          | ✅     |
| Dislikes list               | `test-user-dislikes`         | ✅     |

## Responsive Breakpoints

-   **Mobile**: < 768px (stacked layout)
-   **Tablet**: 768px - 1023px (side-by-side layout)
-   **Desktop**: ≥ 1024px (enhanced spacing and larger elements)

## Testing

-   The page includes built-in validation for all required `data-testid` attributes. Open the browser console to see validation results.



## Notes

-   All external links include `rel="noopener noreferrer"` for security
-   The time display updates every 100 milliseconds
