# UQ Club Discovery Hub

A user-centred web application designed to help university students **discover, compare, and evaluate student clubs more confidently**.

The project combined **user research, iterative product design, and React development** to address a common problem: students can usually find clubs, but often struggle to decide which ones are genuinely a good fit because information is scattered, inconsistent, or too promotional.

---

## Project Overview

The product was developed through multiple iterations of research, prototyping, MVP testing, and refinement.

The final MVP focused on helping students:

- browse and search student clubs
- filter clubs by category and interest
- compare structured club information
- view practical details such as cost, location, activity type, and meeting expectations
- access contact and social links
- join clubs and review joined-club information through a profile page

The broader goal was not simply to make clubs easier to find, but to **reduce uncertainty during the decision-making process**.

---

## My Role

My contribution focused on three connected areas:

### 1. User Research

I conducted student interviews across project iterations to understand how students:

- discover clubs
- compare different options
- decide whether to join
- evaluate whether a club matches their interests and expectations

Recurring themes included:

- practical information such as cost, location, meeting frequency, and event style was important for decision-making
- information was often fragmented across Instagram, websites, group chats, and other platforms
- beginner-friendliness and clear expectations could reduce uncertainty about joining
- social confidence and attending events alone could affect whether students followed through
- students often needed a clearer next step after initially discovering a club

Rather than publishing raw interview transcripts, this portfolio presents synthesised findings to keep the repository focused and protect participant privacy.

---

### 2. Research Synthesis and Product Decisions

I translated interview and MVP-testing observations into structured learning points that could inform product decisions.

One important shift in the project was moving from the assumption that students mainly struggle to **find** clubs toward the more specific problem that they struggle to **evaluate and choose** between clubs.

Examples of research-to-product decisions included:

| Research Insight | Product Implication |
|---|---|
| Students wanted practical details rather than generic promotional descriptions | Present more structured and specific club information |
| Search and category filters helped users narrow down a large number of options | Keep search and filtering as core MVP functionality |
| Users wanted clearer expectations before joining | Improve information about activities, frequency, cost, and beginner-friendliness |
| The profile page could provide more value than simply listing joined clubs | Explore preference-based feedback and profile insights |

This process helped connect qualitative research directly to interface and feature decisions.

---

### 3. Profile Preference Summary

I developed a React component for the profile page:

```text
my-contribution/ProfileInsight_YuejiaBai.js
```

The component provides a simple **Club Preference Summary** based on the user's joined-club data.

The intention was to explore how the profile page could become more informative and reflective, rather than functioning only as a static record of joined clubs.

A simplified example of the logic is:

```jsx
const totalJoined = joinedClubData.length;

return totalJoined === 0
  ? 'Browse the club list and use the filters to find clubs that match your interests.'
  : `You have joined ${totalJoined} clubs.`;
```

This was a small feature within the wider team application, but it connected directly to the research finding that users benefit from clearer guidance and feedback during club selection.

---

## User-Centred Design Process

The broader project followed an iterative process:

```text
User Interviews
      ↓
Problem Hypotheses
      ↓
Test Cards
      ↓
Learning Cards
      ↓
MVP Decisions
      ↓
Prototype Development
      ↓
User Testing
      ↓
Refinement
```

This process helped the team move from broad assumptions toward more specific, evidence-based product decisions.

---

## Selected Research Insights

### Practical information improves confidence

Club names, categories, and short descriptions were useful for discovery, but often not enough for decision-making.

Students wanted more concrete information such as:

- cost
- meeting frequency
- location
- type of activities
- beginner expectations
- what participation actually involves

This suggested that the quality and specificity of club information were as important as the number of clubs displayed.

### Search and filtering reduce browsing effort

Many students already had a rough interest area in mind.

Search and category filtering helped users narrow a large list quickly, so these features remained central to the MVP.

### Discovery is only the first step

Finding a club did not automatically lead to joining.

Students also needed confidence that the club would suit them socially, practically, and financially. This influenced the project toward supporting evaluation rather than only discovery.

---

## Technologies

- React
- JavaScript
- HTML
- CSS
- Git
- GitHub

## Methods

- Semi-structured user interviews
- Qualitative research synthesis
- Test cards and learning cards
- MVP development
- User testing
- Iterative product refinement

---

## Repository Structure

```text
uq-club-discovery-portfolio/
│
├── README.md
│
├── my-contribution/
│   └── ProfileInsight_YuejiaBai.js
│
├── research/
│   ├── user-research-summary.md
│   └── learning-cards-summary.md
│
└── project-context/
    └── mvp-definition.md
```

---

## What This Project Demonstrates

This project demonstrates experience in:

- user-centred software design
- translating qualitative research into product requirements
- iterative MVP development
- React component development
- communicating technical and research contributions within a team
- connecting user evidence to interface and feature decisions
- collaborative GitHub-based development

---

## Project Context

This project was developed collaboratively as part of **COMP1100 at The University of Queensland**.

The full application was created by a team. This portfolio version focuses on the parts of the project most closely related to my own contribution, including user research, research synthesis, MVP testing, and the profile preference summary component.
