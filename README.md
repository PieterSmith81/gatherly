# Gatherly

### _“Connect Locally, Unite Globally”_

A social app to make friends locally and meet up with like-minded people.

## Live Demo Website

### https://gatherly-6tik.onrender.com

## Tech Stack

React, TypeScript, Next.js, Supabase, Docker, GitHub Actions, Husky, ESLint, Prettier.

## Project Outline

### Problem Statement

Loneliness is more prolific in today’s society than ever before. Gen Z, Millenials, and elderly individuals report experiencing high levels of social isolation. Gen Z is said to be the loneliest generation of all time. 22% of Millennials say they have zero friends. And old age loneliness is the highest it's ever been. Existing social media platforms lack focus on building lasting and meaningful connections based on mutual interest and locality.

### Solution

A socially responsible social app that fosters community by helping like-minded individuals find and connect with others within their locality based on shared interests, hobbies and activities. Our app would be aimed at building communities and life-long friendships, both remotely and in-person.

### Approach

- A mobile-first, responsive designed web application.

## MVPs

### MVP1

Just two pages to start with. A profile page and a group chat page. And somewhere (a database) to store the profile and chat data.

- #### Step 1 - Group Chat Page

  **Partially complete** - The real-time, multi-user chat functionality is working. But the Group Chat dropdown filter is not linked to anything yet. So it is not filtering the main chat window according to the selected location/interest chat group yet.

  - A chat page for chatting in your local groups... Think of this as a "WhatsApp group chat" for each location and interest combination in the system.

- #### Step 2 - Profile Page

  **Partially complete** - Just a static example portfolio page for now. Still needs to be be turned into an editable React JSX form.

  - A profile page (based on session authentication initially) containing:
    - Profile picture placeholder (use the user's initials as a profile picture to start with)
    - Email address
    - Name
    - Surname
    - Display Name
    - Location
    - Age
    - Gender
    - Bio
    - Interests (should be able to add multiple interests)
  - Database (for storing profiles, group chats, etc.) using a pre-built service like Supabase's Database service. Supabase databases come with their own auto-generated Data APIs, allowing you to easily create, read, update, and delete data in them. More info here.
    - https://supabase.com/docs/guides/database/overview
    - https://supabase.com/docs/guides/database/connecting-to-postgres
    - https://supabase.com/docs/guides/api

- #### Step 3 - Authentication and Authorisation

  **Complete**

  - User authentication and authorisation using a pre-built service like Supabase's Auth service (https://supabase.com/docs/guides/auth)

### MVP2 (Future Version)

- Search functionality for chat groups based on location and interests

### MVP3 (Future Version)

- Profile pictures
- Profanity filtering for chat messages using, for example:
  - https://www.npmjs.com/package/bad-words
  - https://www.npmjs.com/package/badwords-list
  - https://www.npmjs.com/package/obscenity

### MVP4 (Future Version)

- Local meetups

### MVP5 (Future Version)

- Direct Messages with other users

## Future USPs (Unique Selling Propositions)

These are all still in ideation or under discussion.

- Local friend recommendations based on your interests and friendship circle.
- Interest prioritisation (for better friend recommendations).
- Images and videos in the chat.
- Age filters - chat with people in your chosen age range.
- Custom group icons and descriptions, as set by admins/moderators of that chat group.
- AI-powered chat message safeguards to avoid threats, hate speech, graphic violence, bullying, etc.
- AI-powered profile picture verification.
- AI-powered chat group and direct message moderation.

## Supporting Documentation

### Final Presentation

- Gatherly Final Presentation (as presented on School of Code Bootcamp 17's final project presentation day on Friday, 27 September 2024)
  - https://gamma.app/docs/Innovation-Collective-oox9d4mektcz3du

### GitHub Repo

- GitHub Repo (this page)
  - https://github.com/SchoolOfCode/final-project-innovation-collective

### Planning

- Figma FigJam (Planning and Ideation)
  - https://www.figma.com/board/d9VgoEVmAFsYkY8wTgquKX/Week-13-Planning?node-id=0-1&t=MwFXrHtjVazMh9wF-1

### Team Manifesto Documents

- Team Manifesto Google Doc
  - https://docs.google.com/document/d/1lQ_oJvjzh-zlh6_LrnnaTfCYVEizhvxElQyhaVS_zgk
- Team Manifesto Gamma Presentation
  - https://gamma.app/docs/Team-Manifesto-3cmt7t9votlqm6r?mode=doc
