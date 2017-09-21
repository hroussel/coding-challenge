### CodeNetwork API Description

Create an API to serve as backend for coders's social network application, named CodeNetwork. The API includes these features:
- Allow user to register. No need to submit password or email, just username is enough.
- User can create a post by submitting the post's content.
- Other users can comment on posts by submitting comment's content.
- User can view all posts on the CodeNetwork.
- User can view posts from a specific user.
- User can view all comments on all of his posts.

To keep it simple, authentication and authorization are skipped. The database schema can be minimized like this:
- User (username: string)
- Post (content: string)
- Comment (content: string)
Feel free to add extra fields or use any database types.

### Submission
- Your source code (Github, Bitbucket, Google Drive ... your choice)
- Short and simple documentation for your API

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
