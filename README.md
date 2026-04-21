# integrityx
# IntegrityX

IntegrityX is a simple system I built to make programming assignment evaluation easier and more practical in colleges. Instead of submitting code through portals, students push their work to GitHub, and the system handles evaluation automatically.

## What it does

Whenever a student pushes code to their repository, a webhook is triggered. The backend picks up the latest code, runs a set of predefined test cases, and calculates how many pass.

Based on this, a leaderboard is updated so students can see where they stand.

## Why I built this

In most colleges, assignment checking is manual, time-consuming, and sometimes inconsistent. Feedback also takes time, which slows down learning.

I wanted to build something that:
- gives instant results  
- removes manual correction effort  
- makes evaluation more transparent  
- and actually uses tools like GitHub that students will use in real life  

## How it works (basic flow)

1. Student pushes code to GitHub  
2. Webhook sends a request to the server  
3. Server fetches the latest code  
4. Test cases are executed  
5. Results are stored and leaderboard is updated  

## Tech stack

- Backend: (your actual choice — e.g., Node.js / Spring Boot)  
- Database: (MySQL / Firebase)  
- GitHub Webhooks for automation  

## Current status

Right now, this is Level 1:
- evaluation is based on test cases passed  
- leaderboard is generated from scores  

## What I want to add next

- plagiarism detection  
- code quality checks  
- better feedback instead of just pass/fail  
- maybe some AI-based suggestions  

## Final thought

The idea is not just to automate grading, but to make students more comfortable with real development workflows while learning.
