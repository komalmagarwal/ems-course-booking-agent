# EMS Course Booking Agent

An autonomous AI agent that monitors email notifications from the 
London Business School Enrolment Management System (EMS) and 
automatically books available courses on the user's behalf.

When a course availability notification arrives, the agent parses 
the email, navigates the EMS web interface, and adds the course 
to the shortlist — completing the full booking loop without 
human intervention.

## How it works
1. Monitors inbox for EMS course availability emails
2. Extracts course details from the notification
3. Navigates to ems.london.edu and authenticates
4. Locates the course and executes the Add action
5. Confirms booking and logs the outcome

## Why this matters
Course bidding at competitive business schools is time-sensitive. 
Manual monitoring means missed opportunities. This agent acts 
instantly — at any hour.

**Stack:** Python · Email parsing · Browser automation · 
Agentic AI loop# ems-course-booking-agent
