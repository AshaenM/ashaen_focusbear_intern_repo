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
1. **Clarify confusing permission screens**  
   - Fix the “Allow notifications” flow so tapping “Allow” triggers the correct action.  
   - Minimal dev effort; prevents early drop-off during onboarding.

2. **Simplify habit editing UI (icons)**  
   - Standardize icons for edit, delete, and info.  
   - Mostly front-end work; reduces user confusion.

3. **Clarify blocking rules and timing**  
   - Ensure consistent messaging for blocking schedules (e.g. 5 PM vs. 10 PM).  
   - Medium dev effort; mainly UI text adjustments.

4. **Increase tap target sizes (accessibility)**  
   - Enlarge buttons/icons to meet accessibility guidelines and avoid app store warnings.  

---

### Medium Feasibility / Some Effort Required
5. **Explain features before asking for user input (onboarding carousel)**  
   - Add a feature preview carousel before goal selection.  
   - Requires new screens/components and some dev integration.

6. **Reduce cognitive load in goal-setting (predefined goals)**  
   - Provide suggested goals with optional custom entry.  
   - Some backend integration for goal tracking may be needed.

7. **Align goals with suggested habits**  
   - Map user-selected goals to relevant habits.  
   - High impact but requires backend logic changes.

---

### Lower Feasibility / Larger Effort / Optional
8. **Address paternalistic tone (bear themes, friendly modes)**  
   - Add themed bears, friendly language, and optional modes.  
   - Involves design assets, animations, and dev effort; nice-to-have for engagement.