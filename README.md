# Basic MERN crud server

Basic implementation of a blog application server that runs on localhost

# APIs
## Authentication
- POST /auth/register
- POST /auth/login
- GET /auth/logout

## Application
- GET /posts
- GET /posts/:id
- POST /posts (requires auth)
- DELETE /posts/:id (requires auth)
- PUT /posts/:id (requires auth)

## User administration
- PUT /users/:id (requires admin)
- DELETE /users/:id (requires admin)

# Default port
3009# simple-blog-server
