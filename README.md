# Case Manager Journey

Password-protected HTML prototypes built with Salesforce Lightning Design System 2 (SLDS 2) styling.

- **`index.html`**: the end-to-end complaints journey: customer page → create a case → complaint form → auto tasks → case view → Case Actions → add a new task.
- **`tasks-and-case-view.html`**: a focused study of where a task should open from the case view. It compares a side panel (recommended), a new tab and a modal.

Both pages are encrypted (AES-GCM, key derived with PBKDF2) and unlock in the browser with the password. Nothing readable is stored in this repo.
