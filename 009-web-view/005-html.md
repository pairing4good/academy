# HTML (Hypertext Markup Language)

## Discover
-  watch attached video [![YouTube](https://i.ytimg.com/vi/lHPkQfMu27w/default.jpg)](https://www.youtube.com/watch?v=d84Zuw7fRcA)

## Try
- Site: SoloLearn.com
- Topic: HTML
- Module: HTML 5

## Apply
- Story: 
	- As a pet owner 
	- I want to get contact information
	- So that I can call the pet clinic
	- And drive to the clinic

1) Create this story in Trello
2) add a test that will drive this change
a) locate the acceptance test class named 'PetclinicAcceptanceTests'
b) locate the test method named 'shouldShowWelcomePage'
c) add test assertions to the acceptance test in the following way

```
navigateToWelcome()
.withoutFlashMessage()
.withWelcomeMessage("Welcome")
.withClinicName("[replace me]") //Add this assertion adding the clinic name you want to use
.withClinicAddress("[replace me]") //Add this assertion after you get the previous assertion to pass
.withClinicCityStateZip("[replace me]") //Add this assertion after you get the previous assertion to pass
.withClinicTelephone("[replace me]"); //Add this assertion after you get the previous assertion to pass
```

3) add code through TDD
a) after you have a red test add the clinic name to `src/main/resources/templates/welcome.html`
b) after you have a red test add the address
c) after you have a red test add the city, state, zip
d) after you have a red test add the telephone
4) create a demo of this new feature
a) read the user story
b) demonstrate how to view/use each new feature

## Turn In Your Assignment
- Add a link to your Trello Board
- Add a link to your GitHub repository
- Add links to your story demo videos

## Key Concepts 
- Hypertext Markup Language (HTML), a standardized system for tagging text files to achieve font, color, graphic, and hyperlink effects on World Wide Web pages.
- HTML tag. An HTML code that defines every structure on an HTML page, including the placement of text and images and hypertext links. HTML tags begin with the less-than (`<`) character and end with greater-than (`>`).
- All HTML documents must start with a document type declaration: `<!DOCTYPE html>`.
- The HTML document itself begins with `<html>` and ends with `</html>`.
- The visible part of the HTML document is between `<body>` and `</body>`.
- The `<head>` element is a container for all the head elements. The `<head>` element can include a title for the document, scripts, styles, meta information, and more.
- The `<title>` tag is required in all HTML documents and it defines the title of the document.