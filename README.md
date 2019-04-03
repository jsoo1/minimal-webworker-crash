### How to recreate the issue:

1. `npm install && npx parcel serve index.html`
1. visit the listed url (probably localhost:1234)

  - Expected: No crashing
  - Actual: Crashed with `Uncaught ReferenceError: window is undefined`

