# install-tailwind
Tailwind CSS is self-described as a utility first CSS framework. Rather than focusing on the functionality of the item being styled, Tailwind is centered around how it should be displayed. This makes it easier for the developer to test out new styles and change the layout.

Steps on installing tailwind

step 1: npm install -D tailwindcss@latest postcss@latest autoprefixer@latest

step 2: npx tailwindcss init -p

step 3: go to tailwind.config.js (-in your folder-)

step 4: copy and paste this
purge: ['./pages/**/*.{js,ts,jsx,tsx}', './components/**/*.{js,ts,jsx,tsx}']

step 5: go to _app.js
and
copy and paste this  import 'tailwindcss/tailwind.css'

step 6: npm i -D tailwind-styled-components
in your terminal

step 7: import tw from "tailwind-styled-components"
in index.js

you're good to go
