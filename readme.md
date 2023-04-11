> Demo repository for [Mockend](https://mockend.com/)

# Config

[`mockend.yml`](mockend.yml) describes an API which has `posts` and `comments`. Below you can find a non-exhaustive list of API calls you can make.

To make modifications, fork or copy this config file and [install](https://github.com/marketplace/mockend) Mockend on your repo.

The documentation is available at https://docs.mockend.com

# REST examples

- https://mockend.com/api/mockend/demo/posts – Post
- https://mockend.com/api/mockend/demo/posts/1 – Post 1
- https://mockend.com/api/mockend/demo/posts?createdAt_order=desc – Posts sorted by createdAt
- https://mockend.com/api/mockend/demo/posts?category_eq=one – Posts in category one
- https://mockend.com/api/mockend/demo/comments?postId_eq=1 – Comments for Post 1

# GraphQL examples

- [https://mockend.com/api/mockend/demo/graphql?query=...](<https://mockend.com/api/mockend/demo/graphql?query=%7B%0A%20%20post(id%3A%205)%20%7B%0A%20%20%20%20title%2C%0A%20%20%20%20cover%2C%0A%20%20%20%20comments%20%7B%0A%20%20%20%20%20%20email%0A%20%20%20%20%20%20body%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D>) – Post and Comments

# Try mockend

[Install](https://github.com/marketplace/mockend) 🚀
