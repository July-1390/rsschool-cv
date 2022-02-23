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
Here I use React Hooks, TypeScript

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