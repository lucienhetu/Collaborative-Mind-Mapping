My Mind, collaborative edition
===============================

My Mind is a web application for creating and managing mind maps. It is free to use and you can fork its source code. It is distributed under the terms of the MIT license. This platform extend the original project (http://my-mind.github.io/).


* Get started : https://github.com/lucienhetu/my-mind/wiki
* [News / Changelog](https://github.com/ondras/my-mind/wiki/News)
* [Documentation](https://github.com/ondras/my-mind/wiki)
* New to Mind maps? They are useful, aesthetic and cool! Read more about these special diagrams in [the Wikipedia article](http://en.wikipedia.org/wiki/Mind_map).
* Found a bug? [Open an issue.](https://github.com/lucienhetu/my-mind/issues)
* Not sure how to do stuff? [Check the docs.](https://github.com/lucienhetu/my-mind/wiki)
* Have a feature request? [Open an issue.](https://github.com/lucienhetu/my-mind/issues)
* Have an improvement? [Submit a pull request.](https://github.com/lucienhetu/my-mind/pulls)

OUR GOAL
* Extend the original project to create a workspace where users create a profile and once they are members of a community, they can submit ideas, comment and vote on other ideas, and the most popular ideas are prioritized at the top based on the number of votes the idea receives. Once a promising idea has been identified, ... The team can add more information to the idea, refine it, propose it to leadership and the best ones are selected using sophisticated decision matrix capabilities
* Find external help : Participatory Culture Foundation (Asana)...
 
TODO LIST
* Store data in a local database
  - [X] Integrate web app with RethinkDB
* Realtime collaboration capabilities
  - [ ] Modifications to nodes, aka the contributions, are replicate to user in real-time
    - [X] Push changes to clients
      - [x] Integrate Horizon 
    - [ ] Integrate pushed changes
* Users mgmt
  - Onboarding
    - Adhesion  
      - [ ] Create the forms for adhesion
      - [ ] Integrate ID into nodes authorship (for internal reference)
      - [ ] Username
        - block offensive?
    - [ ] Create document for new users
  - Authentication
    - [ ] Create the forms for authentication
    - [ ] Support majors authentication providers (OpenAuth, Facebook, Google, ...)
  - Preference
    - [ ] Remember open nodes
      - [ ] Save state
      - [ ] Load state
* Contribution mgmt
  - [ ] Concurrency mgmt
  - [ ] Node stages (draft, from draft to accepted, challenge accepted, ACL, Branching)
  
  
![Screenshot](screenshot.png)
