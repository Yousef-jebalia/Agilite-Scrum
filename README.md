# Agilite-Scrum

**Sprint Dash** is a short browser game (about 3 minutes, in French) that teaches students the basics of agile and Scrum.

This game is part of a learning project on agile methods and Scrum.

## The game

You are the Scrum Master of a fictional project, *UniSalles*, a web app that lets students book study rooms. You lead the team through a 5-day sprint:

1. **Sprint Planning**: choose which user stories go into the Sprint Backlog. You can drag them or click them. The team's capacity is 40 story points.
2. **The Sprint**: each day brings one event, such as an overlong Daily Scrum, a client going around the Product Owner, or a blocked developer. Pick the best Scrum answer. A live burndown chart shows how the team is progressing.
3. **Sprint Review and Retrospective**: you get a score out of 100 and a title. A recap explains each mistake, and a final retrospective question closes the sprint.

## How to play

Double-click `index.html`. It runs offline in any recent Chrome, Edge or Firefox, with no installation.

## Editing the content

All game content is kept in plain JavaScript objects at the top of the `<script>` in `index.html`:

- `STORIES`: the user stories, listed in priority order
- `EVENTS`: one event per day, each with 3 choices
- `RETRO`: the retrospective question
- `GLOSSARY`: the glossary terms
- `CONFIG`: the team capacity and the scoring values
