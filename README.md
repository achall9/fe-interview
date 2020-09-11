# BCV Frontend Developer Coding Excercise

## Instructions

Using data from 3 different endpoints (posts, users, properties), build an application that displays the post data as shown in the next images, use them as a guideline. Create a project in github and make sure the app can be started locally for review. After completing everything, record a screencast with a walkthrough over the application and the codebase. Be meticulous about this. 

### Endpoints:
- https://bcv-fe-interview-api.azapata.io/api/posts
- https://bcv-fe-interview-api.azapata.io/api/users
- https://bcv-fe-interview-api.azapata.io/api/properties

#### Post List
![Alt text](images/posts.png?raw=true "Posts")

#### Error Screen
![Alt text](images/error.png?raw=true "Error")

#### Loading State
![Alt text](images/loading.png?raw=true "Loading")

### Product Considerations

1. Some relationships are missing, so not all posts have user or proeprty data. Add the appropiate logic so the the word "Unknown" is shown when there isn't user or property data associated with a post.

2. Show a loading state/loading spinner while the data is being fetched. 

3. The application must not fail silently.

4. Dates should all have the same format.

5. Any social network icon pack can be used. There should be a default icon when no network is present.

6. There is one social network that has two different names, but should be treated as one. 

7. Make sure post content is sanitized.

8. Images should have a placeholder while they're loading. 

9. @mentions should be bold and have a light colored background.

### Technical Considerations

1. Must use react with hooks
2. Must use react-redux with hooks
3. Must git 
4. Must use the fetch API
5. Clean and readable code is highly valued
5. If create-react-app is used, make sure to clean up and remove anything that's not used.



