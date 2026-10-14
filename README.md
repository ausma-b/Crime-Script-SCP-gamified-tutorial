# Crime-Script-SCP-gamified-tutorial

Understanding a crime script and situational crime prevention
An interactive, browser-based learning game for 3026CCJ Fraud and Cybercrime (Griffith University, School of Criminology and Criminal Justice).
Students follow a fictional, composite case of financially motivated sextortion stage by stage. Then they rewind it and look for the points where situational crime prevention could have stopped it. The game is designed to be played live in class (projected, with a tutor narrating) and replayed alone online as part of the gamified reflexive portfolio.
> **Content warning:** this game deals with sextortion and refers to suicide risk as a real-world harm. It never shows sexual images, explicit dialogue or self-harm. A content warning screen appears before play, with an option to read a text-only summary instead.
>
> **Support (Australia):** Lifeline **13 11 14** (24/7) · eSafety Commissioner, [esafety.gov.au](https://www.esafety.gov.au) (image-based abuse reporting)
---
Learning goals
Follow an offence through Leclerc’s (2017) crime script stages: preparation → entry → pre-condition → instrumental precondition → instrumental initiation → actualisation → doing → post-condition → exit.
Map situational crime prevention techniques (Cornish & Clarke, 2003) onto each stage: increase effort, increase risk, reduce rewards, reduce provocations, remove excuses.
Play it
Online: open the GitHub Pages link for this repository (see Publishing below).
Offline: download `index.html` and open it in any modern browser (Chrome, Edge, Firefox or Safari). Nothing to install. Without an internet connection the fonts fall back to system fonts, and everything else works.
Structure
Part	What happens
Content warning	Support links, and a choice between playing and reading a text-only summary
Introduction	The two learning goals
Act 1: The offenders	Lagos, Nigeria: structural strain, status, peer learning and ready-made scripts. Data cards on the World Cybercrime Index and sextortion reports
Act 2: Target selection	Why the offenders target the USA. Meet Alex, 19, a first-year college student. Data cards on victims and the dark figure of crime
Act 3: The script	Six fast scenes from fake profile to escalating demands, with the offenders’ ‘script’ checklist ticking off. Images are never shown
Act 4: Rewind	The core of the game. An introduction to the five SCP techniques, an interactive nine-stage timeline of interventions tagged by actor and technique, a class vote, an alternative ending and evidence-based advice (don’t pay, report, block)
Act 5: Debrief	Summary diagram (crime script × SCP × interventions), three portfolio reflection questions with a copy button, and references
Solo play has 28 screens. Tutor mode adds 4 discussion pauses (32 screens).
Presenting in class
Tutor mode (toggle, top right): adds a discussion pause at the end of each act, a ‘Reveal all’ button on choice screens, a tutor prompt on each timeline stage and an open vote. It also turns off Act 3’s auto-advance.
Keyboard: `→` and `←` move between screens. On the Act 4 timeline, keys `1` to `9` jump straight to a stage.
Auto-play: in solo mode, Act 3 advances every 11 seconds and can be paused. It is off when the viewer has reduced motion turned on.
Layouts are designed for a 1280 × 720 projector and also work on phones.
Accessibility
Body text is at least 20px, with high contrast
Every illustration has a text description
Meaning is never carried by colour alone
Respects the ‘reduce motion’ setting
Fully keyboard navigable
Text-only summary available from the first screen
Privacy
The game runs entirely in the browser. It has no backend, no login, no analytics and no data collection, and it makes no network calls except to load Google Fonts. Nothing a student does is recorded or sent anywhere.
Editing the content
Everything lives in one file, `index.html`. The main things to edit are near the top of the `<script>` section:
What	Where
References and in-text citations	`REF` object (the order of the reference list is set in `REFS`)
Script stages and interventions	`STAGES` array (each intervention has an `actor`, an `scp` technique and `text`)
SCP technique descriptions	`SCP` object
Vote options	`VOTE` array
Reflection questions	`REFLECT` array
Screen text and order	`SCENES` array
Any citation string starting with `[DATA NEEDED` shows on screen as a yellow placeholder, so a missing source is easy to spot.
House style: curled single quotes (‘like this’), no em dashes, and every on-screen claim is either cited or labelled as fictional narrative or concept.
Publishing with GitHub Pages
In this repository, go to Settings → Pages.
Under Build and deployment, set Source to Deploy from a branch, choose main and / (root), then click Save.
After a minute or two the site appears at `https://<username>.github.io/<repository-name>/`.
To update the game, upload a new `index.html` with the same name. The site refreshes within a few minutes.
References
Adeniran, A. I. (2008). The Internet and emergence of Yahooboys sub-culture in Nigeria. International Journal of Cyber Criminology, 2(2), 368.
Bruce, M., Lusthaus, J., Kashyap, R., Phair, N., & Varese, F. (2024). Mapping the global geography of cybercrime with the World Cybercrime Index. PLOS ONE, 19(4), Article e0297312. https://doi.org/10.1371/journal.pone.0297312
Cornish, D. B., & Clarke, R. V. (2003). Opportunities, precipitators and criminal decisions: A reply to Wortley’s critique of situational crime prevention. Crime Prevention Studies, 16, 41–96.
eSafety Commissioner. (n.d.). Deal with sextortion. Retrieved October 14, 2026, from https://www.esafety.gov.au/key-topics/image-based-abuse/deal-with-sextortion
Leclerc, B. (2017). Crime scripts. In R. Wortley & M. Townsley (Eds.), Environmental criminology and crime analysis (2nd ed., pp. 119–141). Routledge.
Thorn. (2025, June 24). The state of sextortion in 2025. https://www.thorn.org/blog/the-state-of-sextortion-in-2025/
Thorn & National Center for Missing & Exploited Children. (2024). Trends in financial sextortion: An investigation of sextortion reports in NCMEC CyberTipline data.
Wolak, J., & Finkelhor, D. (2016). Sextortion: Findings from a survey of 1,631 victims. Crimes Against Children Research Center, University of New Hampshire.
Case note
Alex, Maddie, Tobi, Kunle and Dayo are fictional. The case is a composite based on published research. No real victims or offenders are depicted.
Credits and licence
Developed by Dr Ausma Bernot for 3026CCJ Fraud and Cybercrime, Griffith University.
Licence: Open License.
