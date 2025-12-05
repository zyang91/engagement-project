# Anchor Institution Engagement Tool
Author: Zhanchao Yang <br>
Master of City Planning and Master of Urban Spatial Analytics

MUSA JavaScript Engagement Project


## Purpose & Primary Users

This project is a lightweight engagement tool designed to make it simple for Penn students, staff, faculty, and nearby community members to share quick feedback about places on and around the Penn campus. The intended primary users are:
- Penn Facilities staff and managers who need actionable reports about building conditions, maintenance requests, and community sentiment.
- University City management officials who use community input to prioritize neighborhood improvements and coordinate with campus partners.
- Campus community members (students, staff, faculty, neighbors) who want an easy way to report problems, praise spaces, or suggest improvements.

The audience is specific and operational — not the general public — because submissions are routed to institutional clients who act on the feedback.


## What the tool does

- Let users select a location on an interactive map and submit a short feedback form (issue, compliment, suggestion).
- Allow simple text feedback and optional metadata (photo attachment, category tags such as "cleanliness", "lighting", "accessibility", "safety").


## Datasets and user-provided data

- Campus buildings GeoJSON: polygon features for campus buildings (used for snapping clicks to building footprints and attributing feedback to a building).
- University City boundary GeoJSON: polygon for spatial filtering and context.
- User submissions: each feedback item will include at minimum: timestamp, location (lat/lng and/or matched building id), category, short text comment, and optional photo or contact info (if the user chooses). These user-submitted records will be stored in a database or spreadsheet for clients to review.


