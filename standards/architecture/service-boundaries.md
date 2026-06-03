rules:
Each service owns one business capability.
Services should not directly modify each other’s data.
Shared logic goes into shared utilities, not duplicated everywhere.
Controllers/pages should call services, not contain business logic.
Each major feature gets its own folder/module.

LEON service divisions:
auth-service
user-profile-service
content-submission-service
review-service
notification-service
gamification-service
search-service
media-service
moderation-service
payment-service
analytics-service
