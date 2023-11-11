# React Notes

### Project Structure

- Public - public resources of the app, like images and videos
- src - source code of our application
  - App.tsx - main component of our app
- index.html - basic html for our application
- package.json - information about he project, like the name, the version, dependencies, ..
  - "dependencies": { // Dependencies used in the application
  - "devDependencies": { // Additional dependencies used in development
- tsconfig - Tell our TypeScipt compiler our to compile the code to JavaScript, mostly don't changed
- vite.config.ts - For most of the part do not touch this file

### React Component

Now function based component are more popular to build component in react (more concise and easy to build), but is also ok to use class component.

**PascalCasing** - Always use capital first letter for naming functions

**export default xxx** - Used for reusing the function in other part of the application