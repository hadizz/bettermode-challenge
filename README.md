# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default tseslint.config({
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
});
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react';

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
});
```

# Task Description

# Senior Front-End Engineer

Deadline: September 21, 2024

**Objective:**

We are looking for a talented Senior Front-End Engineer to join our team at Bettermode. Instead of a traditional interview, we invite you to demonstrate your skills and approach by completing the following project assignment. This task will help us understand your proficiency with modern web technologies and how you approach building scalable, responsive applications. We are excited to see your expertise in action and explore how we can collaborate to create exceptional user experiences together.

**Project Overview:**

Your task is to create a responsive web application using Vite, React, TypeScript, and Tailwind CSS that serves as a clone of Bettermode’s post list. The application should feature detailed views, interactive elements, and integrate with GraphQL for data fetching and mutations. Use Apollo client for GQL handling and data caching. This project is designed to assess your technical skills, creativity, and ability to deliver high-quality code.

**Assignment Task:**

**Build a Web Application for Bettermode - Clone the post list functionality**

**Prerequisites:**

1. **Create a Site**
   - Start by creating a site on [app.bettermode.com](https://app.bettermode.com/). Familiarize yourself with the basic setup and functionality.
2. **Explore the Product**
   - Engage with the platform by creating posts and customizing blocks to display a post list. This hands-on experience will give you understanding of what the product is all about
3. **Investigate Using Dev Tools**
   - Use developer tools to dive deeper into the post list functionality. Identify the GraphQL (GQL) API endpoint and examine the payload structure. Pay close attention to how security headers are configured and how session management is handled within the app.
4. **Analyze Post List Mechanics**
   - Gain a comprehensive understanding of how posts are fetched and rendered in the post list. Explore the pagination mechanics and investigate how reaction buttons are implemented and function within the platform.

- **Objective:** Develop a web application that showcases your front-end engineering skills by implementing the following features:

  1. **Post Gallery:** Display a paginated list of posts in a gallery format, with a “Show More” button to load additional posts using Bettermode’s api endpoint.
  2. **Post Details:** Enable users to click on a post to view its details on a separate page, using React Router for navigation.
  3. **Like Feature:** Integrate a “Like” button on both the gallery view and the detail page of each post, displaying the current number of likes and updating this count upon user interaction.
  4. **GraphQL Integration:** Fetch data and execute mutations using GraphQL to manage posts and like counts.

- **Tech Stack Requirements:**
  - **Framework/Libraries:** Vite, React (with functional components and hooks), TypeScript, Tailwind CSS.
  - **Routing:** Use React Router for all navigations within the application.
  - **Data Management:** Utilize GraphQL for fetching data and performing mutations.
  - **Authentication:** Retrieve an access token by creating a site at [app.bettermode.com](http://app.bettermode.com/) and logging in. While hardcoding the token is acceptable, implementing session management with a login page is a plus.
  - **UI/UX:** Ensure the design is clean, responsive, and adheres to modern UI best practices.

**Optional Enhancements:**

- **Server-Side Rendering (SSR):** Implement SSR to improve the initial load time and SEO.
- **Session Management:** Develop a secure login/logout functionality that manages user sessions.
- **Testing:** Write unit or integration tests for key components and functionalities.

**Presentation:**

- **Video Presentation:** Record a video presentation (in Farsi or English) showcasing your web application. Share your screen to demo the application’s features, walk through your code, and explain your design decisions, optimizations, and any optional enhancements implemented.
- **Code Walkthrough:** Highlight key parts of your codebase, including how you structured components, managed state, and handled data fetching and mutations.

**Submission Guidelines:**

- **Deadline:** Please submit your project as a GitHub repository within two weeks of receiving this assignment.
- **Format:** Ensure the repository includes a comprehensive README file with setup instructions and documentation.
- **Delivery:** Share the GitHub repository link by replying to the email through which you received this assignment.

**Evaluation Criteria:**

- **Functionality:** Does the application meet the specified requirements?
- **Code Quality:** Is the code clean, well-organized, and properly documented?
- **UI Design:** Is the user interface aesthetically pleasing, responsive, and aligned with best practices?
- **Use of Technologies:** How effectively have you utilized the required tech stack and implemented the necessary functionalities?
- **Optional Enhancements:** Were any of the optional features (SSR, session management, testing) implemented?

**Working Hours:**

- **Time Zone Requirement:** All applicants must acknowledge that, regardless of their remote working location, they will be required to work based on Eastern Standard Time (EST) to ensure effective collaboration with our team.

**Purpose:**

This project is designed to provide insights into your technical capabilities, problem-solving approach, and ability to build a high-performing web application. By demonstrating your skills in this real-world scenario, you’ll help us see how we can achieve great things together. We look forward to seeing your innovative solutions and exploring how you can contribute to Bettermode’s growth.If you have any questions or need further clarification, please feel free to reach out. Happy coding!

---

**How to Apply:**

1. Review the challenge instructions carefully.
2. Record a video showcasing your solution.
3. Submit your video to **payman [at] bettermode [dot] com** within the next two weeks.
   https://bettermode.notion.site/Senior-Front-End-Engineer-485a0725e4d940c3a01fafe2b5154598
