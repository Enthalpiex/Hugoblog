---
title: Links
links:
  - title: GitHub
    description: GitHub is the world's largest software development platform.
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
  - title: TypeScript
    description: TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.
    website: https://www.typescriptlang.org
    image: ts-logo-128.jpg
menu:
    main: 
        weight: -50
        params:
            icon: link

comments: false
math: true
---

To use this feature, add `links` section to frontmatter.

This page's frontmatter:

```yaml
links:
  - title: GitHub
    description: GitHub is the world's largest software development platform.
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
  - title: The Theoretical Minimum
	description: The Theoretical Minimum is a series of Stanford Continuing Studies courses taught by world renowned physicist Leonard Susskind.
	website: https://theoreticalminimum.com
	image: https://th.bing.com/th?id=ODLS.43067c72-8abb-411e-91aa-9a9ca783afa2&w=32&h=32&qlt=90&pcl=fffffa&r=0&o=6&pid=1.
  - title: MIT OpenCourseWare
	description: MIT OpenCourseWare is an online publication of materials from over 2,500 MIT courses, freely sharing knowledge with learners and educators around the world.
	website: https://ocw.mit.edu/search/
	image: https://th.bing.com/th?id=ODLS.1b2bb948-49ab-40cb-869d-49fbc6357aa9&w=32&h=32&qlt=90&pcl=fffffc&r=0&o=6&pid=1.2
```

`image` field accepts both local and external images.