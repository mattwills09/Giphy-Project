# 'The Office' Themed Giphy Page!
___

For this site we were tasked with creating a themed page, I chose a favorite tv show of mine, "The Office", that will utilize a call to Giphy.com's API, and then use AJAX calls to show the top 10 gif images for the specific searched topic.  The user then also has the ability to freeze and unfreeze the gifs by simply clicking on them, do any custom searches using the search input box, which will add that new button to the page that will call even more gifs from there!  There is also the ability for the user to call more "The Office" themed gifs to the page from pre-set buttons, or through their new custom added buttons, and use the same API calls to provides the top 10 gifs for the button and theme they selected.  Coding the HTML and CSS was more on the simpler side as there was not much body to the page, but the jQuery and AJAX calls were definitely a bit more complicated.  Using past exercises, I was able to layout the adding of the buttons, and the classes and attributes that went along with them, but the most difficult part for me was the appending the 'rating' and the 'gif' to the page.  After researching and reaching out for some help, the solution was basically re-writing the code I had, and got it working from there.  Most likely there was a small typo or something that we could not find, which always seems to be the problem.  But life goes on..

___
![the-office-giphy-1](assets/images/the-office-giphy-1.jpg)
___
![the-office-giphy-2](assets/images/the-office-giphy-2.jpg)
___
![the-office-giphy-3](assets/images/the-office-giphy-3.jpg)
___

The only other difficulty I encountered was found when trying to lay out the gif images in an easier to read layout (in a table or gallery form), and then the pausing and playing the gifs on click.  Basically, I was able to have the gif appear on screen either animated or still, but the clicking to alternate was not working, even though when I inspected the gif added to the screen - I was able to see that it was calling both the 'normal' gif and the 'still' gif url.  After taking some further time on this and talking with a colleague, he was able to show me where the confusion was in the jQuery code - (by adding the <div> class in with the document.on("click")), it was able to be resolved from there.  Then, we also talked about wrapping the entire <div> I made into a parent <div>, so that I was able to edit the layout and look of the called gifs with my CSS also.  Other than that, I added the gif title (to add in a bonus step of grabbing another piece of meta information from the gifs), and added code in the HTML <meta> tag so the page would be responsive on all size screens.  So have some fun and enjoy!
  
### Prerequisites & Installing

To install or run the site, simply navigate to the GitHub hosted link provided below, or users are able to clone the repo to their local machine and run the HTML file from there.

## Built With

* [HTML]
* [JavaScript]
* [jQuery]
* [AJAX]
* [Giphy API](https://developers.giphy.com/) - Giphy.com API Site

## Authors

* **Matt Williams** - *Initial work* - [M Williams Portfolio](https://mattwills09.github.io/portfolio.html)
