# Fitness Influencer Coaching Platform - ER Diagram

This project represents a database design for an online fitness coaching platform.

## Features Modeled

- Trainers and Clients (stored in users table with roles)
- Fitness Plans created by trainers
- Subscriptions purchased by clients
- Sessions (consultations / live training)
- Weekly Check-ins and Progress Tracking
- Payments and Subscription Management
- Trainer Notes and Feedback

## Key Design Decisions

- Single users table with role (client/trainer)
- Subscriptions track plan lifecycle (start & end)
- Check-ins separated from progress logs for normalization
- Sessions and check-ins modeled separately
- Trainer notes stored independently for flexibility

## Entities

- Users
- Plans
- Subscriptions
- Sessions
- Checkins
- Progress Logs
- Payments
- Trainer Notes

## Relationships

- One trainer can create many plans
- One client can have multiple subscriptions
- One plan can have many clients
- One trainer can handle many clients
- One client can have multiple sessions and check-ins

## Submission

This ER diagram is designed using Eraser.io and represents a scalable real-world coaching platform database.
