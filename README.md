# Swathi Pai — Software Engineering Portfolio

A responsive React/Vite portfolio tailored to associate software application engineer roles. Includes a **working, browser-only, synthetic system diagnostics demo**.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. For a production build: `npm run build`.

## Deploy on GitHub Pages, Netlify, or Vercel

1. Create a new GitHub repository and upload this folder's contents (not the zip).
2. In Vercel or Netlify, import the GitHub repository.
3. Build command: `npm run build`; output directory: `dist`.
4. Publish the returned site URL in the job application and on your resume.

## IMPORTANT: personalize before applying

- In `src/App.jsx`, replace empty `GITHUB` and `LINKEDIN` constants with your actual public profile URLs. Empty constants intentionally show a reminder rather than a fake link.
- Add your **real project repositories** to project descriptions when the code is ready. Do not claim code or screenshots that are not actually available.
- Optionally place a tailored resume PDF at `public/Swathi_Pai_Resume.pdf` and add a resume link to the navigation. The current site intentionally has no broken resume button.
- Verify every professional or education claim against your resume.
- The diagnostics demo has **no real hardware, vehicle interface, CAN bus, SAE J1939, or DDS capabilities**. Never describe it as a production vehicle system.
- Do not list clearance/CGP/ITAR eligibility as approved unless formally confirmed; those are employer screening requirements.
- If you need a leaner submission, show the software demo and professional application work first, and keep analytics material secondary.

## Demo logic

The diagnostics panel begins with four synthetic application metrics, allows sample generation, injects a threshold warning, and maintains a short event log. This demonstrates UI state handling and observable behavior, not hardware-level software expertise.

## Important application note

No portfolio can guarantee a callback. Resume fit, required experience, knowledge of CAN/J1939, suitability for security clearance, interviews, and candidate competition still matter. The best way to strengthen this application is to add a real, documented **non-military hardware/software integration** project with tests, Git commits, and honest technical notes.
