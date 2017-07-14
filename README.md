# Nanodegree Feed Reader

This is my project created for the Nanodegree Front End course of Udacity. Using the Jasmine testing framework, we created several tests for an RSS Feeds Reader application.

### Project elements:
- If all feeds have URLs defined and not empty, that is, if each object inside the ```allFeeds``` array has a url defined
and if this attribute is not equal to length zero.
- If all feeds have name defined and not empty, that is, if each object inside the ```allFeeds``` array has a name defined and if that attribute is not equal to length zero.
- If the application menu is hidden by default.
- If the menu button shows and hides the menu successfully.
- If the feed loads successfully, that is, if ```loadFeed``` (asynchronous function) after completing its execution, it generates at least one ```.entry``` element within the ```.feed```
- If you change the feed to actually change the articles, that is, you test if you select another feed in the menu, it actually changes the articles after ```loadFeed``` (asynchronous function) ends its execution.

### How to use
1. You can acess the online app [here.](http://alexmonteirov.github.io/frontend-nanodegree-feedreader)
2. Check the Jasmine section of the application, just bellow, and the tests performed and how they are completed successfully
3. For the right understanding, open the jasmine/spec/feedreader.js file in the directory, to study the Jasmine matchers in the resources
Feed Reader

### How to contribute?
1. [Download](https://github.com/alexmonteirov/frontend-nanodegree-feedreader/archive/master.zip) or clone this repository
2. Navigate to the local directory
3. Open the index.html file in a web browser (I used Google Chrome)
4. Send your change suggestion to me, and I'll evaluate the implementation.

### References
- [Udacity Front-End Web Developer Nanodegree](https://br.udacity.com/course/front-end-web-developer-nanodegree--nd001/)
- [Jasmine Docs](https://jasmine.github.io/api/2.6/global)
- [Rafael Fabeni - Playing with Jasmine](http://www.raphaelfabeni.com.br/brincando-com-jasmine/)
- [HTML Goodies](http://www.htmlgoodies.com/beyond/javascript/testing-javascript-using-the-jasmine-framework.html)
- [@use JSDoc](http://usejsdoc.org/tags-author.html)
- [JavaScript Use Strict](https://www.w3schools.com/js/js_strict.asp)
