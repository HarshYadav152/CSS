# How to setup tailwind CSS

Step 1 : Run the following commands
```
npm i -D tailwindcss
npx tailwindcss init 
```

Step 2 : Update tailwind.config.js file to include this line:
```
content: [*.{html,js}],
```

Step 3 : create src/input.css to include :
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Step 4 : include the src/output.css file to your html

Step 5 : run the following command 
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```