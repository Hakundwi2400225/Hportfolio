# Hportfolio
# Tshifhulufhelwi Hakundwi's Portfolio

A personal portfolio showcasing my skills and projects in web development and cybersecurity.

## Overview
This portfolio highlights my journey as a Computer Science & Mathematics student at the University of Venda, with a focus on web development and cybersecurity.

## Features
- **Responsive Design**: Adapts to different screen sizes
- **Project Showcase**: Displays my recent projects with descriptions and links
- **Contact Information**: Easy ways to reach out to me

## Structure
- `index.html`: The main portfolio page
- `style.css`: Contains all CSS styles for the portfolio
- `images/`: Folder for portfolio images
### linking the website icon with the styling sheets 
- LINKING STYLING SHEETS <img width="827" height="141" alt="image" src="https://github.com/user-attachments/assets/99f5e9d4-eefa-4c25-bff7-e87b245bd1e9" />

- adding Github and Linkedin iconS to be able to style and execute them by html and css.

## Sections Explained
1. **Home**: A brief introduction to who I am
### home navigation set
- HOME SNIPPET <img width="701" height="200" alt="image" src="https://github.com/user-attachments/assets/6dc6bf5a-0b77-4241-8a2e-d88d5eeaf1ff" />

- HOME NAVIGATION OUTPUT <img width="891" height="423" alt="image" src="https://github.com/user-attachments/assets/0d7aefe2-c15e-44ed-a6af-bf1c5bdc0764" />


### About navigation
2. **About**: More details about my background and skills
- ABOUT SNIPPET <img width="753" height="418" alt="image" src="https://github.com/user-attachments/assets/b234bc31-4a5a-4e31-b2a5-cbb5b2b1b747" />

- ABOUT OUTPUT<img width="1263" height="606" alt="AboutNavo" src="https://github.com/user-attachments/assets/6f996a8e-eec8-422e-bb57-c51aeb3664b8" />




### Experience navigation
3. **Experience**: Overview of my experience in web development and cybersecurity.
-EXPERIENCE SNIPPET <img width="767" height="444" alt="expcode" src="https://github.com/user-attachments/assets/6045dc5b-0b02-42b9-b0a0-9ed64aaafc08" />

- EXPERIENCE OUTPUT <img width="1282" height="432" alt="expNavo" src="https://github.com/user-attachments/assets/fe992509-ec59-45e4-986e-cf478cba84fa" />


### Projects navigation
4. **Projects**: Showcase of my projects with links to view them
- PROJECT SNIPPET <img width="902" height="533" alt="projectcode" src="https://github.com/user-attachments/assets/c14a211d-3a36-4bbf-a995-1a80065338ac" />

- PROJECT OUTPUT <img width="1282" height="387" alt="projectNavo" src="https://github.com/user-attachments/assets/84f7c734-393c-493f-a87c-3287e957bd20" />


### Contact navigation
5. **Contact**: How to get in touch with me
- CONTACT SNIPPET <img width="774" height="264" alt="contactCode" src="https://github.com/user-attachments/assets/1527d730-1f55-43cf-86aa-b823ceec804b" />

- CONTACT OUTPUT <img width="1248" height="289" alt="contactNavo" src="https://github.com/user-attachments/assets/7322e1c1-4254-4a08-a4c7-93c320351a2c" />


## Projects Included
- **User Monitoring System**: Allows users to enter credentials and monitor activity.Click view projects to see the system.
- **Web Portfolio**: This portfolio website. Click view projects to see the system.
- **Super Market Database**: allows to store,delete and update the data in the supermarket.

## Contact
- Email: givenhakundwi7@gmail.com / hakundwitshifhulufhelwi1@gmail.com
- Phone: +27 660 495 086
- LinkedIn: [Given Hakundwi](https://www.linkedin.com/in/given-hakundwi-4954443b5)


# Styling the portfolio using CSS
### Body styling
- In the output or the look of my portfolio is based on the decoractions made in css. the main page must repesent itself from other differrent website to show its self that it is a different website.
- body styling snippet<img width="685" height="222" alt="Body styling" src="https://github.com/user-attachments/assets/5e0a1879-4a44-417f-bb8b-13039456124f" />


### header styling
the look of the header wich consist of navigators. the back color on the background. the navigation bar boder-box. The header was set to stay at the top by the z-index key.
- <img width="686" height="350" alt="header" src="https://github.com/user-attachments/assets/5421d68b-4286-4bb5-b502-019a2cb432b6" />
 <img width="1277" height="97" alt="navBarO" src="https://github.com/user-attachments/assets/98adc1bb-cbc4-4f4c-aaef-719c257bc1d7" />


### navigation font color
- since the naviagtion bar background color is black. the best color for fonts is white, for better visibility the font color was whitely bold.
- <img width="615" height="341" alt="LOGcolor" src="https://github.com/user-attachments/assets/ea2133f7-8c25-4aaa-9fa0-6e57a578daf5" />

- the logo command from the font AWSOME website was used for all navigation texts. concluding that also the text "TSHIFHULUFHELWI HAKUNDWI" will work a navigation text navigating from any navigation text to home.

### visit to Github button
- the font color of text "VISIT GITHUB" which white the background button color which the gradeint of blue to purple. when the button is clicked it will lead to the my github profile.
- Github Profile <img width="624" height="357" alt="gitnavi" src="https://github.com/user-attachments/assets/d0c825f2-3848-4025-9375-35bde298240c" />    <img width="1265" height="602" alt="navGITo" src="https://github.com/user-attachments/assets/7e082c0a-9221-4134-81b2-801776cd4900" />



# project

- the projects are stored in grid box.when they are displayed on the output they will be in grid form. the spacing inside the page with and between the grids is 20px together with the gap between the grids. the background colours of the view project button used the the same gradient color from purple to blue.

```css
- projects-grid {            /* Use CSS Grid for layout */
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
  gap: 20px; /* space between cubes */
  padding: 20px;
}
- .view-project-btn {
  margin-top: 10px;
  font-size: 1.5rem;
  padding: 10px;
  background:linear-gradient(to right, rgb(225,0,225), rgb(0,157,225));  /* Gradient background for the button */
  color:whitesmoke;
  border: none;        /* Remove default button corners */
  border-radius: 6px;
  }
```
# Experience styling
 - The text was aligned at the center.on text the text has a header with the black color which is stating the decription of the experience. the gradeint text color was used to spacify only the importants on the experience discription
 - <img width="603" height="401" alt="expc" src="https://github.com/user-attachments/assets/8691473b-14d3-4702-bfc9-84b14c742491" />
   <img width="1282" height="432" alt="expNavo" src="https://github.com/user-attachments/assets/1cfee6df-ec60-4220-a7d0-275b32e7c8c4" />


 # contact styling
 - This CSS snippet styles contact information with a modern, minimal look. The contact p rule makes text appear black but clipped into transparency for a sleek effect, while .contact-info uses flexbox to align icons and text with spacing. Finally, the .contact-info i selector ensures icons are small and consistently black to match the overall design.  
 - <img width="540" height="287" alt="phone" src="https://github.com/user-attachments/assets/9d8192e8-ed67-4747-ab4c-186945b7b523" />
    <img width="1248" height="289" alt="contactNavo" src="https://github.com/user-attachments/assets/914626a3-8e91-4f76-95a6-b7a998b98c36" />

 
 - That is how the code work works, test and see the results..
