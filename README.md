# Case Manager Journey

An end-to-end, password-protected HTML prototype of the complaints case journey, built with Salesforce Lightning Design System 2 (SLDS 2) styling.

**Journey:** customer page → create a case → complaint form → auto tasks (complaint details, investigation, document upload) → case view → Case Actions overlay → add a new ad hoc task.

The page in this repo is encrypted (AES-GCM, key derived with PBKDF2). It unlocks in the browser with the password; nothing readable is stored here.
