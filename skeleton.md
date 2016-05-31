What happens to the layout when you resize the screen to less than 550 px. How do you think that works? If you're stuck, discuss with your accountability group.

The content of the website shrinks down but at the same time makes it big enough to fit the smaller screens.

This was achieved by using a media query. It applies when the screen size becomes smaller than 550 px.

/* Bigger than 550 */
@media (min-width: 550px) {
  .section {
    padding: 12rem 0 11rem;
  }