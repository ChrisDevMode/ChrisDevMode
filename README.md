## Hi!

👨‍💻 I´m Chris.

🇪🇸 I´m from Spain.

👩‍🎨 Front End Developer.

Obviusly, english is not my mother tongue and i will try and  
keep studying so... sorry for any mistake --> remember? 🇪🇸 🤓

At this moment i´m cleaning, updating and adding some new features and project here and i prefer keep clean (empty) for now.  
Between my job and some normal stuff´s life, maybe keep  
a little bit of time but...

Stay tunned.

If you can dream it, you can code it.

```javascript
const chrisGitHub = async () => {
  const resp = await axios.get('/updating-projects');
  if (resp.data.ok === 1) {
    adviceGoodNews(true, 'Here we go! 🚀');
    return;
  }
  adviceGoodNews(false, 'still updating... 😅');
};
```

### SEE YOU SOON! 🧙‍♂️
