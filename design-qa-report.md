# Conducting Design QA Before Release

## What is design QA, and how does it fit into the product development lifecycle?
- Design QA (Quality Assurance) is the process of verifying that the implemented product matches the intended design in layout, spacing, colors, typography, and interactions.
- Ensures usability, accessibility, and brand consistency before release.
- Fits in the **final stage of the development lifecycle** — after implementation but before release — acting as a bridge between design and engineering.
- Helps catch errors that may have occurred during handoff or development.

## What are common design inconsistencies that happen during implementation?
- Misaligned elements or inconsistent spacing and padding.
- Incorrect font sizes, weights, or styles.
- Color mismatches (wrong hex codes or missing design tokens).
- Missing or incorrect animations and transitions.
- Inconsistent button or icon states (hover, active, disabled).
- Accessibility issues (poor contrast, missing alt text, focus states).
- Incorrect responsive behavior on different devices or screen sizes.

## How do designers work with developers to fix issues efficiently?
- Prioritize issues by severity (high, medium, low) to focus on critical fixes first.
- Use screenshots, annotations, and references to the original design.
- Communicate clearly and maintain a collaborative approach, avoiding blame.
- Suggest practical alternatives if a feature cannot match the design exactly (e.g., performance constraints).
- Track issues in shared tools (e.g., Jira, Trello, Figma comments) for accountability.

## What tools can be used for design QA checks?
- **Figma Inspect Mode** – to compare CSS properties, spacing, colors, and typography.
- **Browser DevTools** – to inspect live implementation, measure spacing, and check responsiveness.
- **Zeplin / Figma Variables / Design Tokens** – for verifying consistent styling and reusable components.
- **Contrast checkers** – to ensure accessibility compliance.
- **Screen recording tools** – to check animations and transitions in the live build.

## If a developer says a UI issue isn’t a priority, how would you advocate for fixing it?
- Explain the impact on user experience and trust if the issue is ignored.
- Highlight how visual inconsistencies may affect usability or accessibility compliance.
- Provide data or examples showing potential user confusion or errors.
- Suggest compromise solutions or mark the issue for the next sprint if it’s low-risk.

## What are the risks of skipping design QA before launch?
- Users experience inconsistent UI, reducing trust and perceived product quality.
- Accessibility issues go unnoticed, creating compliance and inclusivity problems.
- Increased bug reports or user complaints post-launch.
- Brand and visual identity may be compromised.
- Potential rework costs and delays if issues are caught after release.

## How can UX designers give clear and actionable feedback to developers during QA?
- Use precise annotations and screenshots highlighting the issue.
- Reference exact design specs (font, color, spacing, component state).
- Categorize feedback by **severity and priority**.
- Suggest practical solutions when a direct match isn’t feasible.
- Maintain professional, collaborative, and respectful communication.

## Task

Since my internship ends this week, I have no time to pick a recently implemented feature and compare it to the original Figma design. Hence my answers below are hypothetical.

**Feature Tested:** Focus Session Summary Screen  
**Reference Design:** Figma File - Focus Session Final Design  

## 1. Discrepancies Found

- **Header Text Size**:  
  - Expected: 24px bold  
  - Actual: 20px regular  
  - Severity: Medium  

- **Primary Button Hover Animation**:  
  - Expected: 0.3s ease-in opacity change  
  - Actual: No animation  
  - Severity: Low  

- **Progress Bar Color**:  
  - Expected: #4CAF50 (success token)  
  - Actual: #66BB6A  
  - Severity: Low  

- **Card Padding**:  
  - Expected: 16px  
  - Actual: 8px  
  - Severity: High  

- **Empty State Icon Shadow**:  
  - Expected: Subtle drop shadow  
  - Actual: No shadow  
  - Severity: Medium  

## 2. Discussion with Developer

- **High-priority fixes**:  
  - Header text size and card padding will be updated before release.  

- **Medium-priority fixes**:  
  - Empty state icon shadow will be added if performance allows.  

- **Low-priority fixes**:  
  - Primary button hover animation and progress bar color will be scheduled for the next sprint.  

## 3. Summary & Suggested Improvements

- Major visual inconsistencies were identified and prioritized by severity.  
- Implementing the high-priority fixes ensures the feature matches the original design closely.  
- Medium and low-priority items can be polished in future updates without delaying release.  
- Clear documentation of issues and agreed fixes improves collaboration between designers and developers.
