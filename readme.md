# Link Tree Page

Max Haider Dev

## Technologies Used

- HTML
- CSS
- JavaScript
- Less for CSS pre-processing

## Design and Layout

This landing page replicates a link tree page and serves as a good base for your own link tree page.

The project uses a responsive design to ensure a good user experience on both desktop and mobile devices. The styles are written in Less, a dynamic preprocessor style sheet language that can be compiled into CSS and run on the client side or server side.

The main styles are defined in the `main.less` file. This file includes styles for the header, profile avatar, profile bio, and social links. It also includes media queries to adjust the layout for different screen sizes.

## How to Use

Here's a demo of how to use the project:

![Demo](https://github.com/maxh33/link-tree-maxHaiderDev/raw/main/src/link-tree-max-haider-dev.gif)

## Deployment

The project is deployed on Vercel. You can access it [here](https://link-tree-max-haider-dev.vercel.app/).

## Running the Page Locally

To run the page locally, follow these steps:

1. Clone the repository to your local machine.

    Cloning a repository means that you're copying the repository from a remote server to your local machine. Here's how you can do it:

    - First, you need to have Git installed on your machine. If you don't have it, you can download it from [here](https://git-scm.com/downloads).
    - Open a terminal on your machine.
    - Navigate to the directory where you want to clone the repository.
    - Run the following command: `git clone https://github.com/maxh33/link-tree-maxHaiderDev.git`

    This will create a new directory in your current directory, named after the repository. This directory contains all the files in the repository.

2. Navigate to the project directory.

3. Compile the Less files into CSS.

    Less is a CSS pre-processor, meaning it extends the CSS language, adding features that allow variables, mixins, functions and many other techniques that allow you to make CSS that is more maintainable.

    Less files don't run directly in the browser, they need to be pre-processed into regular CSS. Here's how you can do it:

    - Install Node.js and npm. You can download them from [here](https://nodejs.org/).
    - Install Less using npm by running the following command in your terminal: `npm install -g less`
    - Navigate to the project directory in your terminal.
    - Run the following command to compile the Less files: `lessc main.less main.css`

    This will create a `main.css` file in the same directory as your `main.less` file, which contains the compiled CSS that can be read by the browser.

4. Open `index.html` in your browser. 

    -Live Server is a simple development http server with live reload capability. It's like having a lightweight, self-contained version of a production server on your development machine.


## Future Improvements

- **Project Demos**: For each project listed, a demo gif could be included to provide a visual representation of the project. This would allow visitors to see the result of the project without having to access the links or download and run the code themselves.

- **Bootstrap Integration**: To enhance the responsiveness and design of the page, future versions could integrate Bootstrap. This would also provide access to a variety of pre-designed components that could improve the user interface.

- **New Projects**: Adding more projects to the portfolio would not only showcase more work but also demonstrate the breadth of skills and experiences. This could include projects using different technologies or projects with different scopes and complexities.

- **Detailed Experiences**: Future updates could include more detailed descriptions of past experiences, including the challenges faced and the solutions implemented. This would give visitors a better understanding of problem-solving skills and adaptability.

- **Developing Skills**: The site could also include a section dedicated to ongoing learning efforts, such as new languages or frameworks being learned. This would demonstrate a commitment to professional growth and adaptability in the fast-paced field of web development.