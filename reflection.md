# PawPal+ Project Reflection

## 1. System Design

**a. Initial design**

- Briefly describe your initial UML design.
-- In my initial UML design. An owner that owns pets and each pet has a lists tasks like walking, feeding, giving medication, and more. Each task would have its own duration, priority, and so on. The scheduler will take the owner's available time for the day and select the tasks by sorting on priority, then duration, and doing what the owner has time left for. It will produce a daily plan that contains the scheduled tasks with the start time and their priorities. Whatever is left after those tasks like if the owner has time for them, then they can work on, but if not then it will just be a list of tasks that were not worked on. 

- What classes did you include, and what responsibilities did you assign to each?
-- The owner will be the one to add pets to the list. Each pet will have a list of tasks that the owner is to complete. It can also get or remove tasks too. Each task will show the time, priority, category, and the preferred time for this.

**b. Design changes**

- Did your design change during implementation?
-- My design did not change, but the added methods and attributes changed a lot. Now there are a lot more than what I have originally have. 
- If yes, describe at least one change and why you made it.
-- N/A
---

## 2. Scheduling Logic and Tradeoffs

**a. Constraints and priorities**

- What constraints does your scheduler consider (for example: time, priority, preferences)?
- How did you decide which constraints mattered most?

**b. Tradeoffs**

- Describe one tradeoff your scheduler makes.
- Why is that tradeoff reasonable for this scenario?

---

## 3. AI Collaboration

**a. How you used AI**

- How did you use AI tools during this project (for example: design brainstorming, debugging, refactoring)?
- What kinds of prompts or questions were most helpful?

**b. Judgment and verification**

- Describe one moment where you did not accept an AI suggestion as-is.
- How did you evaluate or verify what the AI suggested?

---

## 4. Testing and Verification

**a. What you tested**

- What behaviors did you test?
- Why were these tests important?

**b. Confidence**

- How confident are you that your scheduler works correctly?
- What edge cases would you test next if you had more time?

---

## 5. Reflection

**a. What went well**

- What part of this project are you most satisfied with?

**b. What you would improve**

- If you had another iteration, what would you improve or redesign?

**c. Key takeaway**

- What is one important thing you learned about designing systems or working with AI on this project?
