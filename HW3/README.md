# Scalable Notification System Design

## Overview
System for sending notifications (in-app, push, email) at scale.

## Components
- API Gateway
- Notification Service
- Queue (Kafka)
- Workers
- Database
- Cache (Redis)

## Flow
1. Event occurs
2. API creates notification
3. Store in DB
4. Send to queue
5. Workers process and send

## Key Features
- Retry mechanism
- Rate limiting
- User preferences
- Duplicate prevention
