# UQ Club Discovery Hub — Selected Portfolio Contribution

A curated portfolio snapshot from a **team software project** developed in COMP1100 at The University of Queensland.

The full project explored how UQ students discover, compare, and choose university clubs. Across multiple iterations, the team used interviews, hypothesis testing, MVP development, and user feedback to refine the problem from simple club discovery toward **reducing uncertainty when evaluating which club best fits a student's interests and expectations**.

> **Team project note:** This repository is intentionally limited to selected material that reflects my own contribution and the shared project context. It is **not** a copy of the complete team repository, and I do not claim sole authorship of the full application.

## Project Problem

Students can already find clubs through Market Day, social media, friends, and the UQ Union directory. The harder problem is deciding which club to join when information is fragmented, inconsistent, or too promotional to support comparison.

The team therefore focused the MVP on helping students make more confident decisions by bringing structured club information, search, filtering, detailed club profiles, and joining-related interactions into one interface.

## Team MVP

The final React MVP included features such as:

- club browsing and search
- category filtering and sorting
- structured club cards and detailed club information
- contact and social links
- join-club interactions
- joined-club information on the profile page
- responsive desktop and mobile layouts

The project was implemented with **React, JavaScript, HTML, CSS, Git/GitHub**, and an iterative user-centred design process.

## My Contribution

My contribution focused on **user research, synthesis of findings, and profile-related product thinking**.

### 1. User research

I conducted multiple student interviews across project iterations to understand how students discover clubs, compare options, and decide whether to join.

Recurring themes included:

- students wanted practical details such as cost, location, meeting frequency, and what events are actually like
- fragmented information across Instagram, websites, group chats, and other platforms made comparison difficult
- beginner-friendliness and clear expectations reduced anxiety about joining
- social confidence and attending events alone could affect whether students followed through
- users often needed a clearer next step after discovering a club

Rather than publishing raw interview transcripts, this portfolio contains a concise research summary to protect participant privacy and keep the repository focused.

### 2. Learning-card synthesis

I translated interview and MVP-testing observations into learning cards that connected evidence to product decisions.

Three key findings were:

- **Practical information matters more than generic promotion.** Users wanted concrete details that help them compare clubs.
- **Search and filtering reduce browsing effort.** These features were treated as core MVP functionality rather than optional extras.
- **The profile page should provide useful feedback.** A simple list of joined clubs was not enough; the profile could help users reflect on their interests and future choices.

### 3. Profile insight component

I developed the React component:

```text
my-contribution/ProfileInsight_YuejiaBai.js
```

The component provides a small **Club Preference Summary** based on how many clubs a user has joined. It was designed as an experiment in making the profile page more informative rather than using it only as passive storage.

A simplified version of the logic is:

```jsx
const totalJoined = joinedClubData.length;

return totalJoined === 0
  ? 'Browse the club list and use the filters to find clubs that match your interests.'
  : `You have joined ${totalJoined} clubs.`;
```

The component file is included here as a selected code sample. The complete team application remains in the original team repository.

## User-Centred Design Process

The broader project followed an iterative process:

```text
Interviews
   ↓
Problem hypotheses
   ↓
Test cards
   ↓
Learning cards
   ↓
MVP decisions
   ↓
Prototype / product testing
   ↓
Refinement
```

This process helped the team move from a broad assumption — that students struggle to *find* clubs — to a more specific insight: students often struggle to **evaluate and choose** between clubs with confidence.

## Selected Research Insight

One important product-learning chain was:

**Observation:** Club names, categories, and short descriptions were useful but not sufficient for decision-making.

**Interpretation:** Students needed practical and trustworthy information such as meeting time, cost, location, activity frequency, and beginner expectations.

**Product implication:** Keep structured club cards and details, while expanding the quality and specificity of information presented to users.

A second chain was:

**Observation:** Search and category filtering helped students narrow a large list quickly.

**Interpretation:** Many users already had a rough interest area in mind.

**Product implication:** Search and filtering should remain core MVP features because they reduce browsing effort and support comparison.

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

## Skills Demonstrated

- User-centred software design
- Semi-structured user interviews
- Qualitative research synthesis
- Translating user evidence into product decisions
- Iterative MVP development
- React / JavaScript component development
- Team-based GitHub workflow
- Communicating personal contribution within a collaborative project

## Project Context

This work was developed collaboratively as part of **COMP1100 at The University of Queensland**.

This portfolio version highlights selected work relevant to my contribution. Other parts of the full application were developed collaboratively by the team and are not reproduced here as my individual work.
