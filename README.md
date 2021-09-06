# flutter_hash_tag_search

A new Flutter application.

## Task

Overall task: Implement hashtag functionality like in instagram
- 1. If user is simply just typing something, there should be no querying for hashtags
- 2. Once the user starts typing # we are supposed to start querying for the word which comes after the #
- 3. Once the user is finished typing and selects a hash, this word should replace the current word f.e. user types 'awe' and the query result is "'awesome", if he
clicks on the tile with the text "awesome" this string should now replace the String "awe".

Tipps:
- You can find a hash list within the app const file
- Use the search hashtag method within the hashtag service file
- You can use for state managements the stateful widget
