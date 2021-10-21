###### Installation

- git init
- npm install
- npm install -d tailwindcss@latest postcss@latest autoprefixer@latest
- npm init -y (to create package.json)
- npx tailwind init (to create tailwind.config.js)
- create style.css in the root folder
- add tailwind directives
  -- @tailwind base;
  -- @tailwind component;
  -- @tailwind utilities;
- Add script for building css ("dev": "tailwindcss build style.css -o css/style.css")
- npm run dev
- add index.html
- add purge
  -- './src/**/\*.html',
  -- './src/**/\*.js',
- Test tailwind css class
