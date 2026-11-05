# Erick Amollo — Personal Portfolio

A four-page personal portfolio website built with hand-written HTML5 and CSS3.
No frameworks, no build step, no external dependencies — every page is
self-contained with embedded CSS and can be opened directly in any browser.

## Pages

| File | Page | Contents |
|------|------|----------|
| `index.html` | Home | Personal details (name, date of birth, P.O. Box, email, phone, nationality) |
| `experience.html` | Personal experience | Three-column CV table: Date / Institutions attended / Awards given |
| `contacts.html` | Contacts | Contact details, `mailto:` link and feedback form |
| `hobbies.html` | Hobbies | Hobbies in an ordered list and an unordered list |

## Shared features

- The **same navigation menu at the top and bottom** of every page
- Animated header: "Erick Amollo" (48px) sliding continuously left → right
- Green (`#008000`) copyright footer on every page
- Table headers in light blue (`#ADD8E6`), 1px green table borders
- Light blue (`#ADD8E6`) page background on the Hobbies page
- Responsive layout, keyboard-accessible focus states, `prefers-reduced-motion` support

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Personalising

- Replace the inline SVG portrait on the Home page with a real photo
- Update the contact details in `contacts.html` if they change

---

© 2026 Erick Amollo. All rights reserved.
