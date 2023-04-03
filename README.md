I have create Todo React-App using CRA. which look like this.
when It is empty it look like this in Laptop.

![Screenshot from 2023-04-03 17-02-57](https://user-images.githubusercontent.com/122250114/229542203-f459e4d5-ded1-4dee-8abc-cc07593d3576.png)

And In mobile it look like this

![Screenshot from 2023-04-03 17-04-40](https://user-images.githubusercontent.com/122250114/229542342-56738d95-95ec-4a81-bfa4-44d168d8c3dc.png)

If Todo is added in the app then app will be look like this in mobile phone. 

![Screenshot from 2023-04-03 17-26-20](https://user-images.githubusercontent.com/122250114/229542732-6b0cc24d-d4d1-4f9b-a45e-7b1bf8f78841.png)

And It give error like this if someone press enter without add any text. And if someone press 'esc' while typing it exit and input tag is disabled and + button will be showed their.

![Screenshot from 2023-04-03 17-26-41](https://user-images.githubusercontent.com/122250114/229543312-803d0a9e-bb09-4794-adb7-a15e1bbe2ed9.png)

And I used Cookies for storing data which will expires after one day of storing as it is mentioned in lms.

<img src="https://github.com/MdKAMRAN7255/Screenshot/blob/57d66de2bdf6b5dbc4e382cfcb722eb83709d5a3/Screenshot%20from%202023-04-03%2020-17-33.png" >


And In this practical i used react hooks such as *** useEffect & useState *** .
  1. *** useEffect *** : For storing data and inside cookies only if data is valid.
  2. *** useState *** : Is used to add data and toogle between input tag and + button.

And For this App I created 4 Component Inside Component Folder:

Navbar.js: This compnent is containing Header which have Date, Day, Month, Year.

Items.js: This component is child component of AddButton component. Items.js containing List and Custom checkbox. And this component is statefull Component. I used map function to display list from array and inside that map function I put checkbox so that every todo item has their own checkbox that point to that particular item.


AddButton.js: For the Addition Button at the bottom-center of page And Storing data in cookies. It is parent component of Items.js but child component of main.js

These all three component are functional component.

Main.js: This is a class Component and it will render all the above three compnent.

Live Link of this Todo App: https://inspiring-crisp-5edd9b.netlify.app/
