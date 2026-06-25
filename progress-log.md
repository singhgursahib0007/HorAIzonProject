# Living Heritage Project Progress Log

Official progress record for the Living Heritage platform, a community-governed Secwépemc language and culture preservation platform developed under Thompson Rivers University's HorAIzon initiative.

- **Prepared by:** Gursahib Singh, Research Assistant
- **For:** Dr. Latif, Thompson Rivers University

This log is updated incrementally. Each entry summarizes one working session.

---

## 25 June 2026: Accounts and roles, and the review and approval process

Two solid pieces today. I built the way people sign in and the different roles they can have, and then I built the review and approval process that decides what actually gets shared. Together these make sure the right people stay in control of the content.

### Accounts, sign-in, and roles
- Set up secure accounts so each person has their own private login, with a friendly first-time setup when someone new joins.
- Created the different roles people can have (learner, community member, knowledge keeper, reviewer, and steward), so each person only sees and can do what is appropriate for them.

### Review and approval
- Built the process where contributions start out private and must be reviewed and approved before they are shared with anyone.
- Gave reviewers a clear queue to approve content, ask for changes, or decline it, with a record kept of every decision.
- Tied this to the consent system, so if someone withdraws their permission, the related material is taken down.

I have also put the work so far into the GitHub repository you set up, so you can look through the code there whenever it is convenient.

**Status:** On track. The platform now has its accounts-and-permissions layer and its approval process in place. Next I will start on how the actual content, such as recordings and images, is stored and played.

---

## 24 June 2026: Finished the community-ownership controls (part two)

Picked up where I left off yesterday and finished the community-ownership controls. The privacy and access system is now fully in place and working, which I am really happy with because it is the heart of the whole project.

### Finishing the access levels
- Completed the four levels of access (open to everyone, community only, restricted, and sacred) so every piece of content is protected at the right level.
- Made sure the rules are enforced everywhere, so restricted or sacred material can never slip through, even by accident.

### Consent and checking it all works
- Finished the consent system so a contributor's permission can be recorded and withdrawn at any time, and withdrawing it removes the material.
- Spent time carefully testing the whole thing to confirm that private content truly stays private and that only the right people can see each item.

I have attached two screenshots to the report. The first shows the content library, where each item carries its access level and restricted or community-only material stays hidden. The second shows a single item with its access level and the record of where it came from and who it belongs to.

**Status:** Complete and tested. The data and privacy foundation is done. Next I will build sign-in and the different roles people can have.

---

## 23 June 2026: Data foundation and community-ownership controls (part one)

A big setup day. I built the foundation that will hold all of the cultural content, and I started on the most important part of the whole project, which is the set of controls that keep the community in charge of their own knowledge. I got a good chunk of this done today and will finish the rest tomorrow.

### The data foundation
- Set up the underlying structure that will hold every kind of cultural content, including recordings, images, and stories, and made sure each community's material is kept clearly separate and its own.
- Did a lot of careful groundwork here so the rest of the platform has a solid, organized base to build on.

### Community ownership and privacy (started today)
- Began building the system that keeps everything private by default, so nothing is ever shown publicly until it has been reviewed and approved.
- Started setting up the different levels of access (open to everyone, community only, restricted, and sacred) so that sensitive material is properly protected.
- Laid the groundwork for consent to be something that can always be given and withdrawn, in keeping with the OCAP principles we discussed.

I have attached a screenshot of the platform as it stands so far. It shows the early content library, where each item carries its access level, and where restricted and community-only material stays hidden from anyone without permission.

**Status:** Partly complete. The data foundation is in place and the community-ownership controls are set up and working in part. I will finish the remaining access and consent rules tomorrow, and then move on to accounts and roles.

---

## 22 June 2026: Started building the platform (foundations and design)

This was the first proper build day, and a lot came together. I got the platform set up from the ground up and put a full visual design in place, so we now have a real working foundation rather than just planning documents.

### Getting everything set up
- Set up the actual web application that the whole platform will be built on, and organized the project carefully so it stays easy and tidy to keep adding to.
- Put a clean and reliable development setup in place so the quality stays high as the project grows.

### The look and feel of the platform
- Designed the full visual style of the platform from end to end, aiming for something warm and respectful rather than cold and overly technical.
- Chose colours inspired by the Secwépemc land, and picked fonts that display the Secwepemctsín writing correctly, including its special characters, so the language always looks right.
- Built all the main pieces of the interface, such as buttons, cards, menus, and the overall page layout, and made sure everything works in both light and dark mode and stays accessible.

**Status:** On track and happy with the pace. Next I will move on to the data side of the platform and the part that protects community ownership and controls who can see what.

---

## 19 June 2026: Specification refinement and language-resource repository

Incorporated Dr. Latif's feedback into the project specification, and established a structured repository of publicly available Secwepemctsín language resources.

### Project specification updated
- Adopted a working platform name, "Living Heritage," kept distinct from the HorAIzon initiative.
- Added a dedicated subsection explaining how the platform satisfies the OCAP principles (Ownership, Control, Access, and Possession).
- Added Indigenous music as a preserved feature of the platform, with a note on eventually helping learners learn their own music traditions.
- Reframed the use of artificial intelligence to emphasize open-source models that run privately on secure, community-controlled infrastructure.
- Streamlined the document and removed vendor-specific references.

### Public language-resource repository established
- Created a clearly organized repository of publicly available resources for Secwepemctsín, the Secwépemc (Shuswap) language of the Kamloops region.
- Structured into Text, Images, Music, Videos, and Additional Learning Resources.
- Collected language overviews, alphabet and orthography references, word and phrase lists, dictionary and grammar pointers, stories, and academic and government sources, each with attribution.
- Gathered openly licensed images with descriptive metadata, a referenced catalog of music recordings that respects community ownership, a curated list of educational videos, and a directory of courses, apps, organizations, and archives.
- Preserved source links and licensing throughout, following Indigenous data sovereignty principles (OCAP and CARE).

**Status:** On track. Next work focuses on beginning the platform's foundational build.
