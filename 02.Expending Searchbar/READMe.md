## Requirements

- **Search Input**
  - Takes up **⅓ of the width** of its container

- **When the user clicks into the search bar**
  - Input grows to the **entire width** of its parent container with a smooth transition
  - Input **shrinks back to its original size** when the user clicks away
  - Input has a **blue border**
  - **Bonus:** Placeholder text is **not visible** when the user clicks inside the search bar

## Accessibility

- For accessibility, form inputs must always have a **label**
  - Create a label with a valid `for` attribute linked to the input
- Apply CSS rules to **visually hide the label** while keeping it accessible to **screen readers**
  - You do not need to write these rules yourself; standard accessibility patterns may be used
