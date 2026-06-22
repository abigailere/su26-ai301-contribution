# su26-ai301-contribution
# Contribution [4545]: [Inspect organs / Organ damage]

**Contribution Number:** [**1** / 2 / 3]  
**Student:** Abigail Erefah  
**Issue:** [https://github.com/ss14Starlight/space-station-14/issues/4545]  
**Status:** [Phase I / **Phase II** / Phase III / Phase IV] [**In Progress** / Complete]

---

## Why I Chose This Issue

[1-2 paragraphs explaining why this issue interests you, how it matches your skills/learning goals, what you hope to learn]
I chose this issue because I am interested in game development and it aligns with my skill set. I don't have much experience with c# but I have experience with game dev and I usually pick up languages quickly so I don't think that would be an issue. When I saw the project, the premise sounded cool and I liked the collaborative nature of the game. Although it is not marked as a good first issue (the repo doesn't have any right now) I don't think it will be too difficult to implement. I Hope to hone my game development skills and have something production ready for my portfolio beyond independent projects. 
---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]
Community would like to add a feature where players can see the status of organs because right now, it is not possible to see which organs belong to who and whether it is still viable
### Expected Behavior

[What should happen?]


### Current Behavior

[What actually happens?]
Currently there is no way to tell where farmed organs come from or if they are damaged. The state of the organ is important for helping players decide which ones to keep and which to get rid of. 

### Affected Components

[Which parts of the codebase are involved?]
There are a few different types of creatures in this game that have a set of organs. They are group by "system" for example the circulatory system. I am still looking through the folders to understand how specific organs are spawned and how attributes are assigned
---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]
It took me a while to understand hwow to setup my environment and build the project for contribution.All information on how to build the project was located in a separate doc which was really helpful. I had dependency issues that took a few days to work through. I used AI to help me. Currently, I am working on Visual Studios 2022 and the only issue I have is that it cannot recognize .NET even though its there. I can't build from the VS interface but I can from the command line so I will be using that for devlopment. Otherwise everything else is working and I am ready to start working on the issue.
### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]
Because this is a feature request there is no "issue" to reproduce. This is something i will have to implement. I will play through the game to see if I can find a prompt where the information for organs is stored.

### Reproduction Evidence

- **Commit showing reproduction:** [[Link to commit in your fork]](https://github.com/abigailere/space-station-14)
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]
I am still looking through the code to understand exactly how organs are organized but i see that there are groups of "systems" like a circulatory system and digestive system, rather than individual organs. Each system has its own file so I think I can add a component where each organ has an attribute of species type and how much damage it has taken. Maybe also include how long its been taken but that depends on how relevent that peice of information will be for creating the feature the player suggested. I can have those values passed in and stored so that in the UI it can be displayed when a player looks at their organ stash

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
