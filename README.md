To add a dark mode to your Ionic Angular app, you can use the CSS prefers-color-scheme media query. This query allows you to apply different styles based on the user's preferred color scheme, as set in their operating system.

To use this query, you will need to create two sets of styles: one for the dark mode and one for the light mode. Then, you can wrap each set of styles in a @media block that uses the prefers-color-scheme query, like this:

Copy code
/* light mode styles */
@media (prefers-color-scheme: light) {
  /* your styles here */
}

/* dark mode styles */
@media (prefers-color-scheme: dark) {
  /* your styles here */
}
You can then use these styles to style the various components in your app. For example, you can use the ion-content component to apply the dark mode styles to the overall content of your app, like this:

Copy code
/* dark mode styles for ion-content */
@media (prefers-color-scheme: dark) {
  ion-content {
    /* your styles here */
  }
}
You can also use the ion-item and ion-label components to style individual items and their labels in the dark mode, like this:

Copy code
/* dark mode styles for ion-item and ion-label */
@media (prefers-color-scheme: dark) {
  ion-item {
    /* your styles here */
  }
  ion-label {
    /* your styles here */
  }
}
