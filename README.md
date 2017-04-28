# Exercise Description

Implement one of below application:

1. Search engine that displays as much information as possible about given topic as possible. Example: Search engine that finds
    football players and displays list with information about particular player, hes team, photo, social feed, etc.

2. Application that gives as much information as possible about given input. Example: Application that displays weather, map, 
    based on photos, based on current location. Input types are not restricted in any way - imagination is the limit.
 
# Goal

Practising technologies/tools presented on devtalk:
- redux saga
- redux sauce
- reselect 
- apptension's boilerplate stack

# Requirements

- use at least **three** different external API's - the more you use the better
- data obtained from particular API's should be handled asynchronously using redux saga
    (do not wait for all API calls to finish, present data as soon as it comes)
- data obtained from API's should be directly put into application's state as Immutable data and queried with `reselect` (for reselect practice purpose)
- use `reduxsauce` for actions and reducers as configured in boilerplate

# Extra points
- nice interface
- interesting use case for `reselect` (eg. restructuring data, filtering, etc.)
- usage of unusual API's
- utility in real world
- unit tests
 