# CAPSTONE PROJECT: Crea8folio: Professional Portfolio Creator for Business Students
*Source Files not included for now*
![crea8folio](https://github.com/user-attachments/assets/8ec0a72c-3703-4242-a576-89e483db7f8b)

## Introduction
. Hello! welcome to my personal project Crea8Folio!. Crea8folio is a no-code portfolio builder tailored specifically for business students. It’s a platform that empowers students to showcase their skills, projects, and accomplishments in a professional and visually appealing way. The idea behind Crea8folio came from my realization that, unlike computer science majors, business students lack tools to create personalized, interactive portfolios. This project not only aims to level the playing field but also to make portfolio-building an enjoyable and creative process.

## Inspiration
As a computer science student, I’m aware of the importance of a personal portfolio. It's often the deciding factor in securing jobs or internships. However, I noticed that students in non-technical fields, especially business majors, don't have the same resources to showcase their work. While computer science students build GitHub repositories or personal websites, business students often rely solely on resumes or LinkedIn profiles. 

This realization sparked the idea for Crea8folio—a user-friendly platform for business students to showcase their unique skills and experiences.
![image](https://github.com/user-attachments/assets/5bfe66c2-a58c-4922-8ebf-ad9629a7074d)



## Development Process
![image](https://github.com/user-attachments/assets/e5f998e3-6624-4932-88ef-150f006070bc)
Here is a snapshot of what I wanted the final app to look like in terms of where everything was located. Of course, this was based on the fact that I would do this in Reka.JS-- which soon turned out to be not ideal.


### Research and Ideation
![image](https://github.com/user-attachments/assets/afc00fb5-de5d-4a7e-9ccf-94339322f2c1)
The journey started with extensive research into portfolio needs across different majors. I discovered that business students required features like:
- Dynamic content sections (e.g., project showcases, testimonials).
- Customizable templates for branding.
- An intuitive, no-code interface.
- I asked around UW's career service to see if they had any idea of what elements went into a business portfilio.
- I also asked my business friends if they had trouble showcasing their ideas anywhere.

Initially, I planned for a web-based platform but later pivoted to a desktop app after realizing its benefits for offline use and performance. This pivot was a major milestone in the project’s direction.

---

### Transition to a Desktop App
The transition required integrating **React** with **Electron** to build a cross-platform desktop application. Electron provided the tools to run a React app as a desktop app, making it possible to maintain functionality while leveraging local system resources.
![image](https://github.com/user-attachments/assets/9c034215-b024-4982-bb2d-a621105938ec)


Some of the key features added during this phase included:
- **HTML & CSS Code Viewer**: Users can view the generated code for their portfolios.
- **Export Functionality**: Users can zip and download their portfolios for easy sharing.
- **Spectate Mode**: Allows users to preview their portfolio in full-screen mode.

---

### Building the Drag-and-Drop Editor
The most challenging yet rewarding part of the project was building the drag-and-drop editor. To achieve this, I utilized **Grape.js**, a powerful open-source library for creating web builders.
![image](https://github.com/user-attachments/assets/89d507d1-ff17-4716-a6d8-9a9e41798d97)

The thing is that I started with Reka.JS, but soon realized that it does not support JavaScript functionality and I could not make elements reactive. Unfortunetly I realized this halfway in building Crea8Folio.
![image](https://github.com/user-attachments/assets/3abe3326-57c9-4abd-98d2-612e87bbad31)



#### How Grape.js Works
Grape.js is essentially a JavaScript framework that allows users to visually create HTML structures. It comes with a variety of pre-defined components that can be customized. For Crea8folio:
1. **Block-Based Approach**: Users can drag and drop blocks (e.g., text, images, grids) into the workspace.
2. **Styling Customization**: Integrated styling tools let users adjust colors, fonts, and layouts without coding.
3. **Backend Customization**: I spent hours digging into the Grape.js backend library to tweak functionalities and meet the project’s standards.

This editor was particularly tough to implement due to the math required for layering and positioning elements, but the results were worth it. I had to do a lot of library digging in order to tweak Grape.JS to my style.
![image](https://github.com/user-attachments/assets/afd06da3-d64a-4c28-be87-d868bc5f6152)

Here is what the app looked like after implementing Grape.JS and tweaking the library to match Crea8Folio's Style.
![image](https://github.com/user-attachments/assets/9ef344c9-4ccb-42c2-bb65-a032f860edc8)

---

### Tackling Challenges
#### Steep Learning Curve
This project forced me to dive deep into new tools and frameworks. React and Electron integration was a learning curve in itself, but customizing Grape.js took things to another level. I had to research a lot on how to implement Grape.JS core features while keeping my own personal style on it. This took forever.

#### Research-Driven Development
Unlike previous projects, where I jumped straight into coding, this one required me to step back and plan. Researching frameworks, APIs, and drag-and-drop systems was critical.
The number one thing that was importent in my research phase was running usability tests. These allowed me to gain insight on what features to add based on what business students already wanted.
I also spent a lot of time on stack overflow to help answer my questions about any sort of implementation.



---

## Key Features
- **Intuitive Drag-and-Drop Interface**: Users can easily build portfolios by dragging and dropping pre-designed blocks. These blocks consist of photos, text, buttons, videos, headings, navs etc.
- **Custom Templates**: Multiple templates tailored to business students, fully customizable to fit their personal brand.
- **Export Options**: Allows users to download their portfolios as a zipped file. This is done through webpack, a free open source bundler.
- **Spectate Mode**: A full-screen mode for showcasing portfolios. This was actually done after a student told me it was inconvient to keep exporting the website if they wanted to see what it looked like.
- **HTML & CSS Viewer**: Helps users understand the underlying code structure.
- - **Business Friendly Elements**: Of course, I needed specific elements that aligned with the business student and so, I decided to add elements such as graphs, tables, testimonals, brands, and blogs.
- Below is a screenshot of the almost final development stage.
![image](https://github.com/user-attachments/assets/a04df1ca-7efc-4de7-9b50-42e2d7590e05)

And here is the what the code export looked like.
![image](https://github.com/user-attachments/assets/31f09a5f-5cca-4b76-bee2-d2f8cbb8fc1f)


## Final Product:
- here is an example website created with Crea8Folio https://faizandhankwala.github.io/Websitetest/
- and here are some screenshots of the final product.
- ![image](https://github.com/user-attachments/assets/a39b4bf9-6144-4408-be72-d5888c67c455)
![image](https://github.com/user-attachments/assets/973970e8-9a07-4d41-91fa-6dc727a73084)
![image](https://github.com/user-attachments/assets/40998e22-a440-4d5d-8a2a-b992938f7b46)
![image](https://github.com/user-attachments/assets/59ef14d8-977e-441b-bf5b-3b33a7a04aba)


I also made a poster explaining the functionality of Crea8folio. You can see it below.
  ![Final Poster (2)](https://github.com/user-attachments/assets/faa19faf-b5d0-4833-b712-6211b5658ffc)



## Looking Ahead
Crea8folio has come a long way, but there’s still room for improvement. I’m currently focused on:
- Fixing bugs for a smoother user experience.
- Optimizing performance for larger projects.
- Enhancing customization options for templates.
- I also want it to become open source

My goal is to continue refining the platform and, eventually, expand it to serve students across various disciplines.

---
## Files and testimonals. 
-Of course, I had to keep this README short and readable, but if you are looking for an in-depth explanation as well as progress per each stage, below is a file that has every bit of detail and process well explanied. 
[CapStone  Portfolio Final updated.pdf](https://github.com/user-attachments/files/18286451/CapStone.Portfolio.Final.updated.pdf)

