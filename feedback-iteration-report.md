# Iterating Based on User Feedback & Product Constraints

## How do UX designers decide which feedback to act on?
- Look for recurring patterns across multiple users.
- Prioritize feedback tied to core user goals.
- Validate with usability testing or data.
- Align with product vision and roadmap.

## What are best practices for prioritizing UX iterations based on feedback?
- Use frameworks like Impact vs Effort matrix.
- Rank by severity of usability issue (critical blockers first).
- Balance short-term fixes with long-term improvements.
- Involve PMs/devs early to assess feasibility.

## How do product constraints (business goals, development effort) impact iteration decisions?
- Business goals may override user preferences.
- Limited dev resources can delay or reduce scope.
- Technical debt or platform limitations may block changes.
- Deadlines force trade-offs on depth vs breadth of updates.

## How can UX designers advocate for usability improvements in a fast-paced product environment?
- Use data: usability testing metrics, conversion rates.
- Show ROI: link good UX to retention, efficiency, revenue.
- Present prototypes to demonstrate value.
- Collaborate closely with PMs and devs, not just hand off requests.

## If a UX change benefits users but conflicts with business goals, how would you approach the discussion?
- Present evidence of long-term value (loyalty, trust, retention).
- Suggest phased implementation to balance both sides.
- Frame usability as a driver of business outcomes.

## How can designers work with PMs and developers to find compromises between ideal UX and technical feasibility?
- Run joint prioritization workshops.
- Use design critiques with cross-functional input.
- Offer alternative solutions that reduce dev effort.
- Maintain transparency about trade-offs.

## What are the risks of making too many small UX changes too quickly?
- User confusion due to lack of consistency.
- Increased dev/testing overhead.
- Harder to measure which change improved outcomes.
- Risk of design debt from uncoordinated tweaks.

## Task

Upon reviewing the user testing session, here are a prioritized list of 8 UX improvements, considering likely business and technical constraints. I’ve grouped them into High Feasibility / Quick Wins and Medium/Low Feasibility / Larger Effort.

### High Feasibility / Quick Wins

1. Clarify confusing permission screens
- **Issue:** The “Allow notifications” flow was confusing; the “Allow” button wasn’t clickable, only “Continue” worked.  
- **Example:** Pavel: *“I don’t understand that. What’s rate no more? Okay. So it looks clickable. I don’t know. Okay, I understand it’s not clickable…”* (8:14)  
- **Impact:** Prevents early drop-off during onboarding.

2. Simplify habit editing UI (icons)
- **Issue:** Red “X” and pencil icons were confusing; unclear whether tapping deletes or edits.  
- **Example:** Pavel: *“Slightly confused about ‘i’ with growth. I usually think it means information, but it has growth… did not delete so it was kind of scary to tap the red cross.”* (12:42)  
- **Solution:** Standardize iconography.

3. Clarify blocking rules and timing
- **Issue:** Confusion between “block after 5 PM” and “block after 10 PM.”  
- **Example:** Pavel: *“I was told after 5 PM everything will be blocked… now it says after 10 PM they will be blocked, so now I’m not sure.”* (18:09)  
- **Solution:** Ensure labels and timing logic are consistent.

4. Increase tap target sizes (accessibility)
- **Issue:** Buttons/icons were too small; could trigger app store warnings.  
- **Example:** Pavel: *“It becomes quite small, so you might even get a warning from Google, your control is too small.”* (15:55)  
- **Solution:** Enlarge interactive elements to meet accessibility guidelines.

---

### Medium Feasibility / Some Effort Required

5. Explain features before asking for user input (onboarding carousel)
- **Issue:** User asked for guidance before filling out free-text goals.  
- **Example:** Pavel: *“Instead my initial mode was kind of, what is this? What can you offer? How does it work? But now you turn tables and ask me what they want to achieve.”* (11:18)  
- **Solution:** Add an intro carousel showing key features (habit tracking, app blocking, focus sessions).

6. Reduce cognitive load in goal-setting (predefined goals)
- **Issue:** Free-text goals felt overwhelming; Pavel skipped typing and just entered a space.  
- **Example:** *“I’m not sure… usually I just skip this. Sorry, but it’s fine.”* (11:47)  
- **Solution:** Offer suggested goals with optional custom entry.

7. Align goals with suggested habits
- **Issue:** User’s goal “Improve eye health” didn’t match the suggested habits.  
- **Example:** Pavel: *“By the time I already forgot that I said it was a goal, by the time I got to the point of habits.”* (33:28)  
- **Solution:** Map goals → relevant habits in backend logic.

---

### Lower Feasibility / Larger Effort / Optional

8. Address paternalistic tone (bear themes, friendly modes)
- **Issue:** App felt like a strict parent.  
- **Example:** Pavel: *“Instead of the app being my tool that helps me, it becomes a master or a strict parent.”* (24:57)  
- **Solution:** Offer optional bear-themed personas, lighter language, and friendlier notifications.

---

**Summary:**  
- **Quick wins:** Permissions, icons, blocking labels, tap targets.  
- **Medium effort:** Onboarding carousel, predefined goals, habit alignment.  
- **Larger effort:** Bear-themed friendly modes.