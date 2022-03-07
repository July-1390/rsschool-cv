# Ruban Julia
---

### Contacts
---

* __Email:__ juliaruban@seznam.cz
* __Phone:__ +420 608 263 424
* __GitHub:__ [Julia Ruban](https://github.com/July-1390)

### About Me 
---

 Have a little experience with background in Frontend and my main goals: to continue developing in the frontend and to start working in a team. I like to find solutions to problems using JS, I do not really like the layout, this is my weak spot. 
 I had experience in two projects: in the first project, as a Web Developer, I made one themes for site constructor, which included amount of website elements and three layouts. In the second project, as a Frontender, I have been involved into development of project, implemented several features for the site. 

 ### Skils
---

- HTML
- CSS/SASS
- JavaScript (Basic)
- Git
- GitLab
- React (Basic)
- React Router
- REST client (fetch)
- TypeScript

### Code Example
---

It's a small part of my pets' project codebase. A react component that handles user votes on films.
Here I use React Hooks, TypeScript.

Link to my project: [RateFilm](https://july-1390.github.io/rate-film-app/)
Link to the code: [Code](https://github.com/July-1390/rate-film-app/blob/main/src/components/Votes.tsx)

```typescript
const handleSubmit = (newVoteValue: number) => {

    if (!authToken) {
      alert("Only registered users can vote.");
      return;
    }

    const newRating = {
      ...innerRating,
      user_vote: newVoteValue,
    };

    setInnerRating(newRating);

    rateFilm(filmId, newVoteValue, authToken).then((res) => {
      setInnerRating(res.data);
    });
  };
```

### Work experience
---

- ##### Media Plus 
Web Developer (work for 2 month)

Link: https://mobirise.com/
 This site is a free offline app for Windows and Mac to easily create website, landing pages and etc. (https://mobirise.com/). It was a one project job where I made one themes, which included amount of website elements and three layouts.

 - ##### Gramotool
Frontend Developer (work for 3 month)

Link: https://gramotool.ru/
Gramotool is a set of helpful tools for active instagram users.
I have been involved into development of Gramotool project. Help team build web pages based on a specified design and I am like a junior assistant. Examples of work I have done:

- make new pages: "Privacy Policy" and "Download Photo"
- search for instagram accounts
- ui design

Acquired experience with React, next.js, styled-components.

### Languages
---

- English \- Intermediate (according to the online test at [www.efset.org](https://www.efset.org/quick-check))<br>
![EFset Score](/images/english_level.png)
- Russian \- Native
- Czech \-Basic