# BCV Frontend Developer Coding Excercise

## Instructions

Using data from 3 different endpoints (posts, users, properties), build an application that displays the post data as shown in the next images, use them as a guideline.

### Endpoints:
- https://bcv-fe-interview-api.azapata.io/api/posts
- https://bcv-fe-interview-api.azapata.io/api/users
- https://bcv-fe-interview-api.azapata.io/api/properties

#### Post List
![Alt text](images/posts.png?raw=true "Posts")

#### Error Screen
![Alt text](images/error.png?raw=true "Error")

![Alt text](images/loading.png?raw=true "Loading")

### Product Considerations

1. Some relationships are missing, so not all posts have user or proeprty data. Add the appropiate logic so the the word "Unknown" is shown when there isn't user or property data associated with a post.

2. Show a loading state/loading spinner while the data is being fetched. 

3. The application must not fail silently.

4. Dates should all have the same format.

5. Any social network icon pack can be used. 

6. There is a social network that has two different names, but should be treated as one. 

7. Make sure post content is sanitized.

8. Images should have a placeholder while they're loading. 

9. @mentions should be bold and have a light colored background.

### Technical Considerations

1. Must use react with hooks
2. Must use react-redux with hooks
3. Must use the fetch API



