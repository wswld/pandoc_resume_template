$for(header-includes)$
$header-includes$
$endfor$
$for(include-before)$
$include-before$
$endfor$

$firstname$ $lastname$
===========

> (email: $email$ - phone: $phone$)

EXPERIENCE
-----------

$for(experience)$

**$experience.title$**
$experience.employer$$if(experience.city)$ ($experience.city$)$endif$ *$experience.dates$*

$for(experience.description)$- $experience.description$$sep$

$endfor$

$endfor$

SKILLS
------
$for(tech_skills)$$tech_skills$ • $endfor$$for(people_skills)$$people_skills$ • $endfor$

EDUCATION
---------
**$education.institution$** $education.major$

*$education.dates$* $education.city$
$education.description$

CONTACT INFORMATION
-------------------

- phone: $phone$
- email: $email$
$if(homepage)$- website: http://$homepage$$endif$
$if(linkedin)$- LinkedIn: https://www.linkedin.com/in/$linkedin$$endif$
$if(github)$- GitHub: https://github.com/$github$$endif$
$if(twitter)$- Twitter: $twitter$$endif$
