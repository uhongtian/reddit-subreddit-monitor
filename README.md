# Reddit Subreddit Monitor
This project is an external scheduled monitoring service for selected public subreddits.

## Purpose
The service periodically retrieves newly published public posts from selected subreddits within a recent time window (for example, the last 72 hours), stores limited metadata, and generates summaries for external review.

## Data Access
The application only accesses public post data required for monitoring, including:
- title
- permalink
- author
- timestamp
- score
- number of comments
  
## Behavior
This service is read-focused and does not:
- create posts
- submit comments
- send direct messages
- vote
- perform moderation actions

## Example Use Case
Monitor subreddits such as r/ShowYourApp for newly published public posts and generate summaries for internal tracking or notification workflows.
