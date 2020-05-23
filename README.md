# Project Description

## Task One: Semantic Elements
In the file index.html I replaced the elements characterized as div with semantic elements chosen through a process of examining the webpage to discern which div elements were functioning as what in the elements and replacing them with appropriate semantic elements accordingly.

Doing this required some ammendment in the style.css file in order for the webpage to display as desired. An example of this was the navigation tabs displaying differently when the div element containing them was replaced with a nav semantic element. This issue occured because in the css file the div element containing the navigation links was reffered to as ".header div" in three occasions. Changing the word "div" to "nav" in these three instances in the css file solved this problem and made the webpage display as desired once again.

## Task Two: Logical Structure
In the file index.html I examined the code and ensured it the semantic elements were written in a logical structure, in this case being, from top to bottom, Header (containing Nav), Section, Main (containing Articles), Aside (containing Articles) and Footer.

I also ensured that within the code the spacing of the lines were layed out in such a way that made it easy to read. In the code if there was an instance where this was not the case I used the tab key to re-format it in such a way that made it easier to read, making it clear what lines of code were within each element and which closing tag and opening tag were connected.

## Task Three: Alt Attributes
I gave alt attributes to each image on the web pages which are necessary should the images not load or for greater accessibility for the visually impaired. I added alt tags in each img element along with the src tags and wrote in the alt tags descriptions of each image which in most cases were the same as the image id's and file names.

In one case the image was not in the html document but in the css document and therefore in this case I could not use the same method to provide an alt attribute as I did in the other cases. Rather than placing the alt tag in the img element I placed it in the section element with the id "hero" because it was under this id that the image was called in as the background image in the css file.

## Task Four: Heading Attributes
In the file index.html the heading attributes (h1 to h6) must appear in sequential order. I ensured that the heading attributes were ordered hierarchially. The header in the header element was h1, the header in the main element was h2 and the header in the aside element was h3. This was satisfactory as the number after h increased only by 1 each time and didn't jump by more. The footer element was also h2.

## Task Five: Descriptive Title
In order to make the title element concise and descriptive I replaced the word "website" with another title instead. This title was: Horiseon - Home. This title is a combination of the company name and the fact that this webpage is assumed to be the homepage of the website.
