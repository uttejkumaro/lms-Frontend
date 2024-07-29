## LMS Frontend
### Setup instructions

1.clone the project 

```   
    git clone https://github.com/uttejkumaro/lms-Frontend.git
```

2.move into the directory

```
    cd lms-Frontend
```

3.install the dependencies

```
    npm install
```

4.Run the server 

```
    npm run dev
```
### How to setup tailwand in your  project 

1.install tailwand and other dependencies 

 ```
 npm install  -D tailwindcss postcss autoprefixer

 ```
 2.create a postcss.config.js file

 ```
 npx tailwindcss init -p
 ```
 3.Add the files nd extensions to tailwand config in the content property 
 ```
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],

 ```

 4.Add the tailwand directives on the top of index.css file
 ```
 @tailwind base;
 @tailwind components;
 @tailwind utilities;

 ```
 6.Run the server,tailwind should integrated
 












