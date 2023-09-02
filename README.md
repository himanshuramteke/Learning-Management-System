# LMS Frontend


### Setup Instruction

1. Clone the project

```
   git clone https://github.com/himanshuramteke/Learning-Management-System.git
```

2. Move into directory

```
   cd Learning-Management-System
```

3. Install dependencies

```
   npm install
```

4. Run the server

```
   npm run dev
```


### Setup Instruction of Tailwind CSS using Vite

[Tailwind CSS official instruction doc](https://tailwindcss.com/docs/guides/vite)

1. Install Tailwind CSS

```
   npm install -D tailwindcss postcss autoprefixer   
```

2. Create tailwind config file 

```
   npx tailwindcss init -p
```

3. Add file extensions to tailwind config file in the contents property

```
    content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
```

4.Add the tailwind directives at the top of the index.css file

```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
```