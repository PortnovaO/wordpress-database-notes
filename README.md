# WordPress Database Notes

## Important Tables

wp_posts
Stores posts, pages and custom post types.

wp_options
Stores site settings and configuration.

wp_users
Stores registered users.

wp_usermeta
Stores user metadata.

wp_postmeta
Stores metadata for posts.

## Common queries

SELECT * FROM wp_posts LIMIT 10;

SELECT option_name, option_value
FROM wp_options
WHERE option_name = 'siteurl';

SELECT ID, user_login
FROM wp_users;
