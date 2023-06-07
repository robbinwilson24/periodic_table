Periodic Table of Elements
A visually appealing and responsive periodic table of elements created with JavaScript, HTML, and CSS.

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [How to Use / Install](#how-to-use--install)
5. [Credits](#credits)

## Description <a name="description"></a>
This is a full periodic table of elements. The initial version of this was a simple HTML and CSS created as a required task on a Web Development course I was enrolled in. The initial purpose was just to focus on layout, CSS, and extensive use of div tags (hence why the periodic table was coded manually).

I have added additional elements in the form of a modal pop-up that contains information obtained from an API call. The page is visually appealing and functional. However, at present, it is best viewed on larger screens and may not function properly on Internet Explorer. I will work on making it responsive in the future.

### Main page:
![image](https://github.com/robbinwilson24/periodic_table/assets/123034061/a0e7bdc6-ad04-482d-a511-8be82fbeb6f8)

### Modal:
![image](https://github.com/robbinwilson24/periodic_table/assets/123034061/7106373e-b107-4fd1-9ab2-29f283d055b4)


## Features <a name="features"></a>
- API call that retrieves information about periodic elements.
- Modal that appears with details of the element you have clicked on (details obtained from the API).
- Previous and Next buttons that allow navigation between elements when the modal is open.
- Event listeners that enable navigation using the left and right keyboard keys.
- Close button to dismiss the modal.
- Conditional color changes in the modal based on the element being viewed.
- Imported font from Google Fonts.
- Use of DOMpurify to sanitize innerHTML updates.
- Extensive use of CSS for an attractive styling.

## Technologies Used <a name="technologies-used"></a>
This project was created using the following technologies:
- JavaScript
- HTML
- CSS

## How to Use / Install <a name="how-to-use--install"></a>
Installation is simple:
1. Clone the repository to your local machine.
2. From within the Periodic Table directory, Open `index.html` in your browser.

**Note:** This project may not function properly on Internet Explorer.

## Credits <a name="credits"></a>
This page was coded by myself.

With credits to the following:
- **Pubchem** for the details of each of the table elements. [Link](https://pubchem.ncbi.nlm.nih.gov/periodic-table/)
- **Mukund Kumar on RapidAPI** for the API that provided the information in the modal. [Link](https://rapidapi.com/mukundKumar/api/periodictable/)

Feel free to use this page for educational purposes or as a starting point for your own project.
