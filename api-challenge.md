### CoderLink API Description

Create an API to serve as backend for coders's social network application, named CoderLink. The API includes these functions:
- Allow user to register. No need to submit password or email, just username is enough.
- User can create a post by submitting the post's content.
- Other users can comment on posts by submitting comment's content.
- User can view all posts on the CoderLink.
- User can view posts from a specific user.
- User can view all comments on all of his posts.

To keep it simple, authentication and authorization is skipped. The database schema can be minimized like this:
- User (username: string)
- Post (content: string)
- Comment (content: string)
Feel free to add extra fields or use any database types.

### Acceptance Criteria
- Implemented by using Rails framework
- Satisfy the requirements
- Documentation for every endpoints
- Can show and explain the source code

#### Bonus
- Write unit tests
- RESTful API
- Deploy the app to any online server
- Error handler
- Performance optimization
