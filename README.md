# Anthony's Smart Shopping

Anthony has developed a basic price comparison application to better assist him in searching for the best 
television to purchase.  He has created a simple method of scraping the first page of search results 
from Walmart to be displayed in a simple table.

He would like to be able to do more with this application, so he has tasked you with further development.

## Features to be Added

* Anthony would like to be able to search for any given term, and have results displayed automatically (without
  having to reload the page).
* He would like to be able to search not only Walmart, but Kmart as well.  This should be done in a similar
  manner to Walmart (scraping data from their search page).
* He would like the ability to "merge" search results.  For example, if a Walmart search produces a specific
  TV with model # "1234", and K-Mart returns the same TV, the best price should be displayed along with the
  retailer that provides the price.
* He would like to be able to sort results returned from a search by any available column.
* He would like the ability to mark a television as an item of interest.  He should be able to easily view 
  and manage a list of favorite televisions.
* He would like the application to be secured with user accounts, and televisions should be associated with users.

Please also edit the README.md file to explain your logic and any decisions you've made.  Additionally, answer
the following question: If you had more time to work on this, what additional features could you add?

## Instructions

1.  Create a GitHub account (if you do not already have one).
2.  Fork this repository.
3.  Implement the features described above using any gems or libraries you deem appropriate.  Web scraping must
    be performed using Mechanize.
    * You must perform  the test in a single sitting, and are allowed no more than 4 hours.
4.  When complete, email a link to your forked repository to `technology@tlsgltd.com`, preferably with a
    tag or branch containing the completed code.
