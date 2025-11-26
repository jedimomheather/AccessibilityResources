# ✅ Accessible & Inclusive Design Checklist  
*A practical checklist for building accessible Power Platform solutions.*

---

## 🧱 1. Layout & Structure
- [ ] Group related content into clear, logical sections  
- [ ] Keep screens uncluttered with sufficient whitespace  
- [ ] Maintain consistent layouts between screens or pages  
- [ ] Break long processes into smaller, progressive steps  
- [ ] Use descriptive headings and section titles  
- [ ] Avoid relying on hover-only tooltips for essential information  

---

## 🎨 2. Colours, Contrast & Visual Clarity
- [ ] Text/background contrast meets WCAG AA (4.5:1 minimum)  
- [ ] Icons and graphical elements are paired with text labels  
- [ ] Colour is not the only method used to indicate meaning  
- [ ] Custom colour palettes are checked with WebAIM Contrast Checker  
- [ ] Avoid bright, high-saturation colours that cause eye strain  

---

## ✏️ 3. Text & Content
- [ ] Use plain, friendly, and concise language  
- [ ] Keep instructions short and specific  
- [ ] Avoid jargon, acronyms, or unclear terminology  
- [ ] Use consistent wording for actions and labels  
- [ ] Error messages explain what happened *and* how to fix it  

---

## ⌨️ 4. Keyboard Navigation
- [ ] All interactive controls have **TabIndex ≥ 0**  
- [ ] Decorative elements use **TabIndex = -1**  
- [ ] Tab order follows a logical reading flow  
- [ ] Focus indicators remain visible and are not removed  
- [ ] Entire app can be used without a mouse  

---

## 🔊 5. Screen Reader Support
- [ ] Every functional control includes an **AccessibleLabel**  
- [ ] Decorative images use empty alt text (`""`)  
- [ ] Functional images include descriptive alt text  
- [ ] Hidden labels/regions are used to add extra context where needed  
- [ ] No essential content is visually hidden from screen readers  

---

## 🧠 6. Reduce Cognitive Load
- [ ] Limit the amount of information shown at once  
- [ ] Use conditional visibility to hide irrelevant choices  
- [ ] Ensure navigation is predictable and consistent  
- [ ] Include progress bars or step indicators for multi-step tasks  
- [ ] Keep notifications and alerts minimal and purposeful  

---

## 📝 7. Forms & Data Entry
- [ ] Required fields are clearly indicated  
- [ ] Real-time validation highlights problems immediately  
- [ ] Placeholders provide examples, not critical instructions  
- [ ] Replace long dropdowns with search or auto-suggest  
- [ ] Provide sensible default values where possible  

---

## 📱 8. Responsiveness & Touch Targets
- [ ] Layout adapts to different screen sizes  
- [ ] Touch targets are **44px x 44px** or larger  
- [ ] Interactive elements have spacing to prevent accidental taps  
- [ ] Horizontal scrolling is avoided where possible  

---

## 🔍 9. Testing & User Feedback
- [ ] Run Power Apps **App Checker** for accessibility issues  
- [ ] Test full user journeys with keyboard only  
- [ ] Test with screen readers (Narrator, NVDA, JAWS if available)  
- [ ] Check colour contrast using WebAIM  
- [ ] Validate with users who have diverse needs or contexts  
- [ ] Re-test after any major redesign or update  

---

## ⚡ 10. Performance & Readability
- [ ] Screen loads do not contain unnecessary delay  
- [ ] Text scales correctly at 200%+ without breaking layout  
- [ ] No flashing or flickering animations  
- [ ] Layouts feel predictable and stable during navigation  

---

## ⭐ Summary
Accessible design means creating solutions that are:  
✔ Clear  
✔ High-contrast  
✔ Keyboard-navigable  
✔ Screen-reader compatible  
✔ Low in cognitive load  
✔ Tested early and often  

---
