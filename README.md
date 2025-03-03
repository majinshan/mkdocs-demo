# Demo to test pagetree and awesome-nav

- add - "*" to the first line of .nav.yml, pagetree are normal. url: your-domain/shanghai

- shanghai/.nav.yml
```
nav:
  - "*"
  - court-title: court
  - procu-title: procu
```


- Don't add - "*" to the .nav.yml, pagetree(children) show its sibling. url: domain/beijing

- beijing/.nav.yml
```
nav:
  - court-title: court
  - procu-title: procu
```


