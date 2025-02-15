# Character-counter
This is used to count  the number of characters in the line including spaces .<br>
This code creates a simple **Character Count** web application using **HTML, CSS, and JavaScript**. Here's a summary of how it works:

## **Functionality**
- It includes a **textarea** where users can type text.
- A **counter** below the textarea dynamically updates to display the number of characters entered.

## **Breakdown**
1. **HTML Structure**
   - A centered `div` (`.box`) contains:
     - A heading (`<h2>Character Count</h2>`)
     - A `<textarea>` for user input
     - A `<p>` element displaying the character count (`<span id="count">0</span>`)

2. **CSS Styling**
   - The page has a **full-height**, centered layout (`.container` using `flexbox`).
   - The `.box` has a **border, padding, rounded corners**, and a **background color**.
   - The `textarea` has a **fixed size**, rounded corners, and a **border**.

3. **JavaScript Logic**
   - An **event listener** is added to the `<textarea>` to detect input changes.
   - It updates the `<span id="count">` with the current **character length** of the input.

## **Behavior**
- As users type in the textarea, the counter **automatically updates** to reflect the total characters entered.

This is a **basic but effective** implementation of a live character counter. 
