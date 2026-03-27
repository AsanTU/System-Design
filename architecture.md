# Architecture Diagram

Client → API Gateway → Notification Service → Queue → Workers → External Services
                                  ↓
                              Database
                                  ↓
                                Cache

Components:
- API Layer
- Queue
- Workers
- DB
- Cache
