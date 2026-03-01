# 4-Week Personal Coding Roadmap (Beginner → Small App)

## Your profile (used to design this plan)
- **Experience:** Complete beginner
- **Goal:** Understand coding basics and build something small
- **Time available:** 1–2 hours/day (~42 hours total in 4 weeks)
- **Preferred path:** Fastest/easiest route to web + app exposure
- **Tools available:** ChatGPT Plus + Gemini Pro
- **Background:** MBA (strong business/product thinking)

---

## Strategy (fastest realistic path in 4 weeks)
To maximize speed and still learn fundamentals, focus on:
1. **One core stack first:** HTML/CSS/JavaScript + Firebase (web app).
2. **Then app exposure:** Wrap web app as mobile using Capacitor OR build tiny React Native demo in Week 4.
3. **Vibe coding safely:** Use AI to accelerate, but require yourself to explain every block you ship.

---

## What you can realistically achieve in 4 weeks
By the end, you should be able to:
- Explain variables, functions, conditionals, loops, arrays/objects, and async basics.
- Build and deploy a small web app with auth + simple data storage.
- Use AI assistants to scaffold and debug without becoming fully dependent.
- Produce a basic mobile app version/prototype of your web app.

---

## Daily structure (1–2 hours)
Use this template every day:
- **10 min:** Review yesterday + define today’s tiny goal.
- **35–55 min:** Learn one concept using a guided resource.
- **35–45 min:** Build (or improve) your project.
- **10 min:** Reflection log:
  - What did I build?
  - What broke?
  - What did I learn?
  - One question for AI tomorrow.

---

## 4-Week Plan (with free resources)

## Week 1 — Foundations + first mini project
**Outcome:** Understand core coding concepts and publish a tiny static project.

### Topics
- Internet/web basics
- HTML, CSS, JavaScript fundamentals
- Git/GitHub basics
- Prompting AI for coding with verification

### Free resources
- **HTML/CSS:** freeCodeCamp – Responsive Web Design  
  https://www.freecodecamp.org/learn/2022/responsive-web-design/
- **JavaScript basics:** freeCodeCamp – JavaScript Algorithms and Data Structures (first modules)  
  https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/
- **Friendly intro videos:** Programming with Mosh (YouTube, free intros)  
  https://www.youtube.com/@programmingwithmosh
- **Git/GitHub:** GitHub Skills (Introduction to GitHub)  
  https://skills.github.com/

### Build task (ship by end of week)
- Create a **Personal Habit Tracker (v0)** static page:
  - Add/remove habits
  - Mark done/not done for today
  - Store data in browser localStorage

### AI/vibe coding exercise
- Ask ChatGPT/Gemini: “Generate starter code for a habit tracker in vanilla JS.”
- Then ask: “Explain this line-by-line for a beginner.”
- Then **manually edit** at least 20% (styles, naming, one new feature).

---

## Week 2 — Real web app basics (frontend + backend-lite)
**Outcome:** Turn static project into a simple real app with login + database.

### Topics
- JavaScript deeper: functions, arrays/objects, async/await
- API concepts (request/response, JSON)
- Firebase fundamentals: Auth + Firestore
- Basic product thinking: user flow and MVP scope

### Free resources
- **JavaScript deepening:** The Odin Project – Foundations (JS sections)  
  https://www.theodinproject.com/paths/foundations/courses/foundations
- **APIs + JS in browser:** MDN JavaScript Guide  
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
- **Firebase docs (free):**  
  https://firebase.google.com/docs
- **Optional structured course:** Full Stack Open (free, use selected parts only)  
  https://fullstackopen.com/en/

### Build task
- Upgrade Habit Tracker to **MVP web app**:
  - Email login
  - Save habits per user in Firestore
  - Simple dashboard (streak count + completion %)

### AI/vibe coding exercise
- Prompt pattern:
  1. “Give me the smallest working implementation for Firebase email auth in plain JS.”
  2. “Now explain security risks and what to fix.”
  3. “Write tests/check steps to verify this works.”

---

## Week 3 — Productization + deployment + quality
**Outcome:** Deploy publicly, improve UX, and add minimal quality practices.

### Topics
- UI/UX polishing
- Error handling and loading states
- Basic testing mindset
- Deployment

### Free resources
- **Design/UI quick wins:** Refactoring UI free articles  
  https://www.refactoringui.com/
- **Accessibility basics:** Web.dev accessibility  
  https://web.dev/learn/accessibility/
- **Deploy web app:** Vercel docs (free tier)  
  https://vercel.com/docs
- **Alternative deployment:** Netlify docs (free tier)  
  https://docs.netlify.com/

### Build task
- Deploy your app publicly
- Add:
  - Empty/loading/error states
  - Basic onboarding message
  - Mobile-responsive layout
  - One “wow” feature (e.g., weekly chart)

### AI/vibe coding exercise
- Use AI as code reviewer:
  - “Review this file for readability and bugs. Return only must-fix items.”
  - “Suggest one improvement that reduces complexity.”

---

## Week 4 — App exposure + capstone wrap-up
**Outcome:** Keep one codebase and get app-platform exposure quickly.

### Recommended easiest path
- Keep your web app.
- Package it for mobile using **Capacitor** (fastest route).

### Alternative path (if curious)
- Build a tiny React Native demo with Expo separately.

### Free resources
- **Capacitor docs:**  
  https://capacitorjs.com/docs
- **Expo (React Native) docs/snacks:**  
  https://docs.expo.dev/
- **PWA as another path:**  
  https://web.dev/learn/pwa/

### Build task
- Produce one of these by end of week:
  1. Packaged mobile shell (Android is easiest to test), or
  2. PWA installable version of your app
- Record a 2–3 minute demo video of your product
- Write a short post: problem, users, features, next steps

### AI/vibe coding exercise
- “Help me create release notes and onboarding text for non-technical users.”
- “Create a one-page technical architecture summary for this app.”

---

## Interactive checklist (copy into your notes and tick daily)
- [ ] Set up GitHub account + repo
- [ ] Finish HTML/CSS module
- [ ] Finish JS fundamentals module
- [ ] Build localStorage habit tracker
- [ ] Learn Firebase auth basics
- [ ] Add login
- [ ] Add Firestore data model
- [ ] Show dashboard metrics
- [ ] Deploy app (Vercel/Netlify)
- [ ] Improve mobile responsiveness
- [ ] Add one standout feature
- [ ] Package for mobile or PWA
- [ ] Record demo video
- [ ] Publish README + next steps

---

## Vibe coding rules (so AI helps you learn, not replace learning)
Use this **80/20 rule**:
- 80%: let AI accelerate boilerplate
- 20%: you must understand and edit critical logic

For every AI-generated code block, do all 5 checks:
1. Can I explain what each function does?
2. Can I rename variables to something clearer?
3. Can I add one small change myself?
4. Can I test at least one edge case?
5. Can I describe why this approach is safe enough?

If any answer is “no,” don’t ship yet.

---

## Suggested free tool stack
- **Editor:** VS Code
- **Web hosting:** Vercel or Netlify (free tier)
- **Database/Auth:** Firebase free tier
- **Version control:** GitHub
- **Design quick mockups:** Figma free tier
- **AI coding copilots:** ChatGPT Plus + Gemini Pro (already available)

---

## Copy-paste prompt templates for ChatGPT/Gemini

### 1) Learning prompt
"I’m a complete beginner. Teach me [topic] in 15 minutes using simple language, one analogy, and one mini exercise. Then quiz me with 5 questions."

### 2) Build prompt
"I’m building a habit tracker web app using vanilla JS + Firebase. Generate only the smallest working code for [feature]. Add comments for every important line."

### 3) Debug prompt
"Here is my error and code. First explain likely root cause in plain English, then give a minimal fix, then list how to test the fix."

### 4) Product prompt
"Act like a PM + engineer. Given this app idea, define MVP scope for 4 weeks at 1–2 hours/day. What should I cut?"

---

## Stretch goals (only if ahead of schedule)
- Add Stripe test payments (test mode only)
- Add basic analytics (PostHog free tier)
- Build second mini app: simple expense tracker

---

## Expected milestones by time budget
- **~10 hours:** Basic JS confidence + static mini app
- **~20 hours:** Auth + database integrated
- **~30 hours:** Deployed MVP with decent UX
- **~40+ hours:** Mobile packaging/PWA + demo-ready

---

## What to do if you get stuck
- 30-minute rule: if blocked >30 min, ask AI with full error and context.
- If still blocked, reduce scope by 50% and ship smaller.
- Keep momentum > perfection.

