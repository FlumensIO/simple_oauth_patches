# simple_oauth_patches

Drupal 8 simple_oauth module patch that allows better mobile app communication. 
 - Improves refresh token generation and revoking.
 - [Allows authentication by email](https://www.drupal.org/project/simple_oauth/issues/2908437).
 

## To apply
- `cd simple_oauth`
- `curl https://raw.githubusercontent.com/FlumensIO/simple_oauth_patches/main/simple_oauth.patch | git apply -v`
