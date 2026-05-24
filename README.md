# app-support

Support and legal pages for indie iOS apps by Eiji Akiyama, hosted on GitHub Pages.

## Apps

- [Punctual](./punctual/) — Meeting alarms that bypass Silent and Focus mode.

## Structure

```
app-support/
├── styles.css          shared styling for all app pages
└── <app-name>/
    ├── index.html      support / getting help
    └── privacy.html    privacy policy
```

## Adding a new app

1. Create a new folder named after the app
2. Copy `index.html` and `privacy.html` from an existing app folder
3. Update the app name, GitHub repo URL, and privacy content
4. Add a link to the new app in this README
