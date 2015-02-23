Optimizations Made:

Changes for Page Speed Score:
load fonts via javascript
load some js asynchronously
compress large images


Changes for Pizza Page main.js:
create items array only once
reduce pizza count from 200 to 24
calculate each of the 5 phases only once
pull document.body.scrollTop only once per update


Changes for Pizza Resizing:
Get the array of randomPizzaContainers just once
