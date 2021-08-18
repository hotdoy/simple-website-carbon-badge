# Website Carbon Badges

This is a stripped down version of the [Website Carbon Calculator](https://websitecarbon.com) made by [Wholegrain Digital](https://wholegraindigital.com)
You can see this version being used [here](https://getwheat.ca) (check the footer).

## Installation

Adding the badge to your site is as simple as inserting the following lines into your markup where you would like the badge to appear:

```html
<script src="carbonbadge.js" defer></script>
<div id="carbonbadge"></div>
```

## More Info

To reduce data transfer and server load, the badge caches the result on the user's device and will only make a maximum of one API call per day for each page it is embedded on. If a user visits the same page more than once within a day, the result will have been cached.
