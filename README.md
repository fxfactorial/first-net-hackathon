# Python tasks

1. Write code that takes a location of (latitude, longittude), set of keyword, and given sentiment
   score between 0, 1 and returns all tweets within a given radius that satisfy these parameters.
   So your function would
   look like:

   ```python
   def task_one(latitude, longitude, keyword_set, sentiment_score, radius):
     pass
   ```

2. Python HTTP server that accepts JSON payloads of location and tweets data, then performs analysis on
   whether group of tweets in that location is bad, like something about to go down, say in a corner
   of a 10,000 person event. Then if threshold met, it alerts police, which then lets the police
   use a python program that sends push notification to people in the affected location.

3) Related to `1`, this task searches all over say a zipcode across all media sources, performs
   analysis about where crime might be, then sends push notificaiton to relevant people using fancy
   new radio tower tech

Some libraries to be used: (importable)

requests, json, http
