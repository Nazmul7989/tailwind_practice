# tailwind_practice
This is tailwind practice project

# Initialize npm

```
npm init -y
```

# Install Tailwind
```
npm install -D tailwindcss
```

# Create Tailwind configuration file
```
npx tailwindcss init
```

# Configure Tailwind configuration file tailwind.config.js
```
module.exports = {
  content: ["*.html"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

# Add the Tailwind directives to your CSS src/input.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

# Start the Tailwind CLI build process and include package.json file
```
"build" : "tailwindcss -i ./src/input.css -o ./dist/output.css -w"
```

# Build the css 
```
npm run build
```

# Start using the Tailwind css
```
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="/dist/output.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>
```

# Add this for vscode user .vscode/setting.json
```
{
    "css.validate": false,
    "tailwindCSS.emmetCompletions": true
}
```

