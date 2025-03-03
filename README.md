# Demo to test pagetree and awesome-nav

- add - "*" to the first line of .nav.yml, pagetree are normal: domain/shanghai
shanghai/.nav.yml
nav:
  - "*"
  - court-title: court
  - procu-title: procu


- Don't add - "*" to the .nav.yml, pagetree(children) show its sibling: domain/beijing
beijing/.nav.yml
nav:
  - court-title: court
  - procu-title: procu


