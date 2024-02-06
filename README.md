# alfred-ghost
Alfred workflow to search Ghost posts.

## prerequisites
- Ghost Pro
-  [jq](https://github.com/jqlang/jq)
-  set your domain ({here}.ghost.io) and Ghost Content API key to environment variables.

## Usage

- `ghost n`: create new post
- `ghost o`: open Ghost dashboard
- `ghost s {query}`: search ghost post from title with query
  - `enter`: copy the post url to clipboard
  - `shift-enter`: open the post
