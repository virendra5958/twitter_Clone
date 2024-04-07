Technologies Used
Backend:
Node.js
Express.js
MongoDB
bcrypt for password hashing
JSON Web Tokens (JWT) for authentication
Frontend:
React
Redux for state management
Axios for HTTP requests
Material-UI for UI components
API Endpoints
Authentication:
POST /api/auth/register: Register a new user.
POST /api/auth/login: Login an existing user.
Users:
GET /api/users: Get all users.
GET /api/users/:id: Get user by ID.
PUT /api/users/:id: Update user profile.
DELETE /api/users/:id: Delete user account.
Tweets:
GET /api/tweets: Get all tweets.
GET /api/tweets/:id: Get tweet by ID.
POST /api/tweets: Post a new tweet.
PUT /api/tweets/:id: Update tweet.
DELETE /api/tweets/:id: Delete tweet.
Likes:
POST /api/tweets/:id/like: Like a tweet.
DELETE /api/tweets/:id/like: Unlike a tweet.
Retweets:
POST /api/tweets/:id/retweet: Retweet a tweet.
DELETE /api/tweets/:id/retweet: Undo retweet.
