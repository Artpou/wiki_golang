# WIKI_GOLANG API DOCUMENTATION

## Open Endpoints

* [Login](docs/login.md) : `POST /api/login/`
* [Create Account](docs/user_add.md) : `POST /api/users/`

## Endpoints that require Authentication

### Article related
* [Show Article](docs/article_show.md) : `GET /api/articles/:id_article`
* [Show Articles](docs/articles_show.md) : `GET /api/articles/`
* [Add Article](docs/article_add.md) : `POST /api/articles/`
* [Delete Article](docs/article_delete.md) : `DELETE /api/articles/:id_article`
* [Update Article](docs/article_update.md) : `PUT /api/articles/:id_article`

### Comment related
* [Show Comment](docs/comment_show.md) : `GET /api/comments/:id_comment`
* [Show Comments](docs/comments_show.md) : `GET /api/comments/:id_article`
* [Add Comment](docs/comment_add.md) : `POST /api/comments/`
* [Delete Comment](docs/comment_delete.md) : `DELETE /api/comments/:id_comment`
* [Update Comment](docs/comment_update.md) : `PUT /api/comments/:id_comment`

### Current User related

* [Show Info](docs/user_show.md) : `GET /api/users/`
* [Delete self](docs/user_delete.md) : `DELETE /api/users/`
* [Update info](docs/user_update.md) : `PUT /api/users/`
