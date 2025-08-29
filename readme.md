## WELCOME TO ( সহজ সরল সিম্পল ) ASSIGNMENT-005

### 📅 Deadline For 60 marks: 29th August, 2025 (11:59 pm ⏱️)

### 📅 No Deadline For 50 marks

### 📅 Deadline For 30 marks: Any time after 29th August.

---

## ✅ Main Requirements (50 Marks)

### 1. Navbar

- **Website name & logo** on the left as Figma
- **Heart icon, coin count (default-100), and Copy Count** on the right as Figma

---

### 2. Hero Section

- **Background Gradient** in the Whole Section
- **A Relevant Logo** at the top-center
- **Section Title** in the center
- **A Relevant Slogan** in the bottom Center

---

### 2. Main Section

This Section will have layout as figma

<table border=1 width="100%" cellpadding="50">
<tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
 </tr>
 <tr>
    <td colspan=9 >Card Section</td>
    <td colspan=3>History Section</td>
 </tr>
</table>

### Emergency Hotline Section

- **Show Minimum 6 cards**. Each card will contain:
  - Icon or Image
  - Relevant Name
  - Relevant Name in English
  - Hotline number for calling
  - Category Badge
  - 💗 icon at left
  - **2 buttons** at the bottom: Copy and Call with icons as Figma

### History Section

- **A white Background** in the whole section
- **History Title with icon** at the top-left as Figma
- **Clear History Button** at the top-right as Figma

---

### 3. Responsiveness (5 Marks)

- Website should be fully **responsive for mobile devices** (implementation up to you)

---

## Functionalities

### 4. Heart Icons

- Clicking on the 💗 **heart icon** of any card will increase the count in the Navbar

---

### 5. Call Buttons

- On clicking a card's **Call Button**, following actions will happen:
  - Show an **alert** with a message including the service name and number
  - Each call will **cut 20 coins**. Reduce Coin after each click.
  - If coins are less than 20, show a relevant alert and terminate the process.
  - Add this service into the **Call History section** with:
    - Service name
    - Service number

---

### 5. Call History Section

- Show all called services with name & number. This will empty initially. when call button clicked it will filled dynamically.
- A **Clear History button** on the right
- Clicking this button will remove all data from call history

---

## Create Readme

You have to create a `Readme.md` file. and write down following questions. Dont Try to copy paste from AI Tools. Just write what you know about these. If you don't know , then search , learn , understand and then write.

### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

Answer: Here are the differences between getElementById, getElementsByClassName, and querySelector / querySelectorAll:
getElementById() Selects a single element by its id and returns an Single element or null if does not exists.
getElementsByClassName() Selects elements (multiple) by their class name and returns live HTMLCollection.
querySelector() Selects the first element matching a CSS selector and returns Single element or null if doesn't exists. Useful when there is no id defined.
querySelectorAll() Selects all elements matching a CSS selectorand returns a static NodeList.

2. How do you **create and insert a new element into the DOM**?

Answer: To create and insert a new element into the DOM: First, need to create an empty element by document.createElement('div');
Then, add some content to it by either plain text using newDiv.textContent or html content using newDiv.innerHTML.
Then, we can add some styling if we need by using newDiv.style
Finally, we need to pick a element and then insert it by using element.appendChild(newDiv);
Also, we can prepend instead of append by using element.prepend(newDiv);

3. What is **Event Bubbling** and how does it work?

Answer:Event Bubbing: In javascript it is a mechanism where an event triggered on a target element propagates upward to its parent elements, and then to the root of the DOM.
How it works: When an event occurs on an element, it first triggers on the target element and then "bubbles up" through the ancestors in the DOM hierarchy, triggering any event listeners attached to those ancestors. What is the benefit of Event Bubbling: Instead of adding event listeners to every individual element (which can be inefficient), we can add a single event listener to a parent element. The parent element will catch events from its child elements because of event bubbling. Which increases performance and saves memory.

4. What is **Event Delegation** in JavaScript? Why is it useful?

Answer: Event Delegation: Event delegation is a technique in JavaScript where a single event listener is attached to a parent element, instead of attaching event listeners to individual child elements.
Why is it useful: It improves performance by reducing the number of event listeners attached to multiple child elements, especially in scenarios where there are many child elements or dynamically added elements. Also, it simplifies the code by centralizing event handling, making it easier to manage.

5. What is the difference between **preventDefault() and stopPropagation()** methods?

Answer: Difference between preventDefault() and stopPropagation():
preventDefault(): It prevents the default behavior associated with an event from occurring. It is used when we want to stop the browser’s default action for the event. For example, preventing a form submission or preventing a link from navigating.
stopPropagation(): It prevents the event from bubbling up or propagating to its parent elements in the DOM. It is used when we want to stop the event from reaching other event listeners higher up in the DOM tree.

---

## 🧪 Challenges Part (10 Marks)

- On clicking the **Copy button**, show an alert and **increase the copy count** (3 Marks)

- Hotline number will be **copied on click** so it can be pasted anywhere (4 Marks)

💡Hint: You can ask for Help from `ChatGPT` Mamma . Just copy the below prompt , generate answer. use it with your own way.

```bash
I have a card with some text and a button inside it. I want that when a user clicks the button, some specific text from the card is copied to the clipboard using JavaScript. Please provide the code and explain it step by step.
```

- After clicking on the **Call button**, the **exact time of the call** will be shown in the Call History section (3 Marks)

💡Hint: Search Google with that below question

```bash
How to get current local time in js
```

---

## ⚙️ Technology Stack

- HTML
- CSS ( Vanilla , Tailwind CSS , DaisyUI , Others - wheatever you like )
- JavaScript ( Vanilla only. No Framework / Library Allowed )

---

## 📌 Rules

- ✅ Minimum **5 meaningful commits** required
- ❌ No Lorem Ipsum or dummy placeholder text. Use **relevant content only**

---

## 🔗 What to Submit

- 📂 **GitHub Repository**
- 🌐 **Live Link**

---

# Let's Code and Achieve your Dream 🎯
