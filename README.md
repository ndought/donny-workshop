# Notes for JS seminar

HTML- Used for structure
CSS- Used for style
JS- Used for user interaction

## Session One
Whenever we refer to  or see document (document.querySelector) in the code it is referring to the 'DOM'.

DOM- (document object model) - an actual object in the browser that we want to manipulateby using javaScript.

QUERYSELECTOR- What we use to grab instances of the code we are working with.
    * Use querySelector when getting single instance
    * Use querySelectorAll when getting every instance on page

. = class
(#) = id

PAGINATION- a way to limit the amount of things you are getting and also a way to specify in list where you are getting items from (like the 5000 photos on the jsonPlaceholder website) "get me 20 of these things from index 0-5 and 15-30"

Do all the stuff!

// What do we want done? We want nav list to display when nav button is clicked
// We are waiting of this event
<!-- navButton.addEventListener("click", () => {
  navList.classList.toggle("hidden");
}); -->
^^ the hide stuff/show stuff JS

// Add image for avatar
<!-- const photoEndpoint = "https://jsonplaceholder.typicode.com/photos/89";
const photoElement = document.querySelector(".about__avatar-container img"); -->

// the fetch executes and gets (what is in here)
//you should always have a .then and a .catch
// have to be inside of a fetch when using .json method
// what you put in .then is always going to be a method of some sort
//catch block is going to handle errors coming back to you
// finally block happens whether you get a positive or negative(error)response


<!-- const photoRequest = fetch(photoEndpoint); 
photoRequest 
  .then((response) => {
    const photoData = response.json(); 
  }) 
  .catch((error) => {
    console.error(error);
  }) 
  .finally(() => {
    console.log("Fetch complete!");
  });  -->




### Assets

- [Placeholder Info](https://jsonplaceholder.typicode.com/) 
^^ public api ^^