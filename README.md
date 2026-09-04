# AI Usage
- Generated Color Palette
- Simple SKU generation for every object
- Simple Hover Animation for object cards
- How to include field name inside field
- JSON parsing debugging
<<<<<<< HEAD
- copy/paste "Running Locally Instructions"
=======
- copy/paste "Instructions to run locally..."
>>>>>>> 6d67b4e (Pushing A2 Code)

# Jersey Collection

A two-tier web app for cataloging soccer jerseys. You can add a jersey through the form and it immediately shows up as a card below with a team, player, number, size, and price, plus a server-generated SKU (e.g. `BUL-23`). Existing jerseys can be edited in place or deleted, all without a page reload. Layout uses **CSS Grid** for the card collection and **flexbox** for the entry form.

To run locally:

```
npm install
npm start
```

Then open `http://localhost:3000`.

## Technical Achievements

<<<<<<< HEAD
- **Tech Achievement 1:** Built as a single-page app. Submitting the form POSTs to `/submit`, and the server responds with the full updated dataset (including the newly computed `sku` derived field), which the client re-renders immediately — no page reload.
- **Tech Achievement 2:** Added the ability to modify existing data, not just add/delete. Each card has an edit icon that swaps it into an inline form pre-filled with that jersey's current values; saving sends a `PUT` to `/jerseys/:id`, the server recomputes the derived field, and the card returns to its normal view with the new data.
=======
- **Tech Achievement 1:** Built as a single-page app. Submitting the form POSTs to `/submit`
and the server responds with the full updated dataset (including the newly computed `sku` derived field), 
which the client re-renders immediately — no page reload.
- **Tech Achievement 2:** The ability to modify existing data not just add/delete. 
Each card has an edit icon that swaps it into an inline form pre-filled with that jersey's current values 
saving sends a `PUT` to `/jerseys/:id` -> the server recomputes the derived field and the card returns to 
its normal view with the new data.

## User Review
    1. Relation: Friend   -    Initials: R.A. (Prefers not to share name)
    2. Before the final draft, the user made a comment about the input field names being outside the fields,
    and that they should be put inside the fields themselves for a simpler look and better space mangament.
    3. The user made a comment that was this web app explains itself without any instructions and that it was
    very convenient for new users.
    4. Based on their feedback, I repositioned field names to be inside field space and fixed text inline-ing 
    to support screens with different ratios and sizes.
>>>>>>> 6d67b4e (Pushing A2 Code)
