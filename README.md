# Tailwindcss
3 ways to strt tailwind css with your code editor.

*** Install from CDM
*** Install as PostCSS Plugin
*** Install Tailwind CLI 

So, i am using CLI system to create a project.
But, there is a prerequisite to run tailwind css.

Must have to have isntall more than node js -v at last 12.3.0

Let's check node with node -v

So, 

npm inint -y

npm i -D tailwindcss (Install for developer dependencies)

Install plugin to your vs code called Tailwindcss Intelligence 

npx tailwindcss init

Create two folder and name should be src and output.

Create a file into src folder called tailwind.css although it can be anything.

Write below code into the tailwind.css 

@tailwind base;
@tailwind components; 
@tailwind utilities;

Create a folder called .vscode in the root folder and create a file name setting.json


Put this code into the setting.json file 
{
  "css.validate": false,
  "tailwindCSS.emmetCompletions": true
}


Paste below code into the package.json file 
======================================================
"build": "tailwindcss -i ./src/tailwind.css -o ./output/tailwind.css -w"














