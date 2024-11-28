## Assignment

### Brief

Write your answers for each question:

Question 1:
Imagine you are hired by a startup company for a school to implement their IT infrastructure as their IT consultant. n your own words (300 words or less), describe how could implementing Scrum help their IT team improve their productivity.

```
Scrum is an agile framework which helps to deliver value incrementally in a collaborative way. The Scrum Team is made up of the *Product Owner*,*Scrum Master* and *Developers* each with different responsibilities. The increment of valuable work are delivered short cycles called *Sprints*. The sprint cycle consist of *Sprint Planning*, *Daily Scrum*, *Sprint Review* and *Sprint Retrospective*.

Sprint Planning sets out the work needed to be done for the sprint based of previous measure of a team's velocity.
Daily Scrum inspect the progress towards the sprint goal.(e.g yesterday task completed,today task to do and blockers)
Sprint Review inspect the outcome of the sprint.
Sprint Retrospective plans way to increase quality and effectiveness.

The three artifact that are created by Scrum would be:
Product Backlog - are all activities associated with product refinement. (e.g user story which are align with the vision of the business needs)
Sprint Backlog - are the activities that are assigned for the particular sprint. If the activities are not completed, they are placed back to the sprint backlog.
Product Increment - are new features that are added to the product.

```

Question 2:
Write ten (10) user stories for a book-borrowing website for a library. Write it in the format: `As a ____, I want to ____, so that _____`.

```
As a user, I am able to search for a book and know its location so that i know that the given book would be there when i visit that library.

As a user, I am able to view the return date of the books that i borrow so that I would be able to return the book on time and avoid late return fee.

As a user, I am able to be recommended trending books that are align to what i like so that I would be more interested to use the app and borrow more books.

As a user, I am able to share my profile and show my friends the books I am reading so that we are able to connect through a common interest in a particular book.

As a user, I am able to view the latest events that is happening in the library so that I am able to be updated and attend library events.

As a user, I am able to borrow ebooks online so that I do not have to worry about going to the library to get/return the books.

As a analyst, I am able to analyst the data such as number of books return/not return so that I would be able to account for the lost of books.

As a analyst, I am able to analyst the data such as number of unique users so that I would be able to account for the number of users that is using the library services.

As a librian/admin, I am able to view the status of the books so that I am able to account for the books in my library.

As a librarian, I am able to create blog/event post so that I am able to create content for user and update them of the events.
```

Question 3:
Define [Acceptance Criteria](https://resources.scrumalliance.org/Article/need-know-acceptance-criteria) for 3 to 5 user stories out of the 10 user stories you have defined.

```
1. As a user, I am able to view the return date of the books that i borrow so that I would be able to return the book on time and avoid late return fee.
*Acceptance Criteria*
Given that user borrowed a book
When user preview the books borrow
Then user is able to see the books borrowed.
Given that user borrowed 10 book
When user preview the books borrowed
Then they will be able to see 10 books.
Given that user view the url of other users books borrowed,
When they probiew the books borrowed by others,
Then they should not be able to view the due date.(privacy)

2. As a user, I am able to borrow ebooks online so that I do not have to worry about going to the library to get/return the books.
*Acceptance Criteria*
Given that user borrowed an ebook,
When user borrowed a book and passed the return date,
Then the book should be not available to user.
Given that user has already borrowed books to the limit,
When user tries to borrow more,
Then they should not be able to.
Given that when user has late panalty fee for the library,
When user tries to borrow,
Then should not be able to borrow till they pay the fine.

3. As a user, I am able to be recommended trending books that are align to what i like so that I would be more interested to use the app and borrow more books.
*Acceptance Criteria*
Given user open the app,
Then visit the homepage,
Then they should be able to view the recommended books to borrow.
Given user has not filled up their preference,
Then visit the homepage,
They should be able to view a generic recommended books page.
Given that user does not have an internet connection,
When they visit the homepage,
Then they should see a locally cached recommended books page.
```

### Submission

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL.

### References

_Example of Referencing Classmate_

Referenced the code block below from Terence.

```js
function printMe() {
  console.log("I am a reference example");
}
```

_Example of Referencing Online Resources_

- https://developer.mozilla.org/en-US/
- https://www.w3schools.com/html/
- https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github
