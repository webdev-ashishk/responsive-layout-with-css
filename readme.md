# 21 day of responsive layout challenge

## Day-01 Use width with percentages & avoiding heights ? px <<<<<<< %

- create a div with id root and place content and set the with:500px margin: 0 auto to make div center and see this is responsive or not ?
  A: No
- #NOTE By default a div is reponsive .
- Q[2]: why by defualt a div is reponsive ?
- A: A div width is block level of element with width:100%;

- Q[3]: My parent div width is 80% and now i set my child width:50% then what is exact width of the div is now ?
- A: 40%

  > child width 40%= (80% / 2) .

- #NOTE- As We know by default website is resonsive we made some changes in css to make unresponsive

## Day-02 em <<<<<<<<< rem

- em works with respect to parent div .
- rem works with respec to root div .

## Day-03 min-width <<<<<<<<< max-width

- fixing the size of div in respective on increaseing the size of screen we can fix the size of max-width in pixels .
- max-width:750px : when screen size increase the width of the div is fixed .
- width: 80% : when screen size decrease the width of the div behave reponsive .
