# API Design

## Create Notification
POST /notifications

Request:
{
  "user_id": "123",
  "type": "message",
  "content": "You received a new message",
  "channels": ["in_app", "push", "email"]
}

Response:
{
  "status": "success",
  "notification_id": "abc123"
}

## Get Notifications
GET /users/{user_id}/notifications
