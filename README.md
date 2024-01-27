# TailwindCssProjects
<b>Before contributing Setup Your Computer as Described below</b>

npm init  
npm install -D tailwindcss postcss autoprefixer vite  
npx tailwindcss init  

//Add the paths to all of your template files in your tailwind.config.js file.  
/** @type {import('tailwindcss').Config} */  
module.exports = {  
&nbsp;&nbsp;  content: ["./src/**/*.{html,js}"],  
&nbsp;&nbsp;  theme: {  
&emsp;    extend: {},  
&nbsp;&nbsp;  },  
&nbsp;&nbsp;  plugins: [],  
}  

//Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.  
@tailwind base;  
@tailwind components;  
@tailwind utilities;  

//Add "start":"vite" to your scripts in package.json  
//Run npm run start command to start a dev server  

<B>For more information on how to have a production setup for Tailwind CSS follow the link:</B>
<a href="https://tailwindcss.com/docs/installation/using-postcss">Tailwind CSS</a>
