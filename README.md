# UliousPage

To run: open vscode, open terminal with ctrl + `, type npm start in terminal and press enter

Overview: UliousPage is a bootstrap project of mine to create a landing page for my own social media marketing agrency built upon the nucampsite we created for one of our bootstrap nucamp projects, inside is a homepage giving an explanation of what it is, how I can help them with their marketing and how to set up an appointment, the site includes a contact page in which you can fill in your info and then submit although the functionality of that is a work in progress as with the reserve consultation, for now these are just for show

What went well:
-The styling turned out very well especially with the name of the business at the top middle of the page with the image in the background of the car, personally I like how it ended up with the car showing up on smaller size screens but shows up as the top which is a brickwall which looks aesthetically pleasing

-Bootstrap makes it very simple to put the bulk of your code in an html file for one page which makes it easy to find where something went wrong or where to add some code easily

What issues I overcame:
-Ran into an issue in which the image with the car on it with the text that reads turbocharge your marketing in which I could not figure out how to put that image on the page without it taking up the entirety of the page, this is where I learned the importance of using containers to create a section on top of a background, after figuring that out it came to just be a matter of using an img src and adding styling with css to the class I created for the image

-Ran into an issue with adding text over the turbocharge your marketing image in which I couldn't figure out how to add the text without having to save the image with the text on it already, to solve this I created a class inside of a col and for the style I put the position as absolute to the img which allowed it to stay fixed on the img and then all I had to do was move the text to the desired position

-Ran into an issue in which the borders around the goals was too close to the words and overlapping, to fix this I researched how to add space to text inside of a border, found the info I needed which was to increase the width and height and to add padding to the style which allowed it to be at the desired size

What I learned:
-Learned how to keep one page to be in one html file
-Learned how to use sizing styles to achieve desired look of site
-Learned how to add text over imgs
-Learned how to use modals to create a popup form

What I want to improve:
-I want to add functionality to the submit buttons so that when I submit to the reserve consultation it brings shows a reservation made screen and sends out the info to somewhere such as an email or to a database same with the contact us form
-I would like to make this more responsive so that on mobile it looks relatively the same as it does on a desktop
