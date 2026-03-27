# Data Model

## notifications
- id (UUID)
- user_id
- type
- content
- status
- created_at
- read

## user_preferences
- user_id
- email
- push
- in_app

Indexes:
- user_id
- created_at
