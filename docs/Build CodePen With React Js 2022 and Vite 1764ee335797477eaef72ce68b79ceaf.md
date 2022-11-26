# Build CodePen With React Js 2022 and Vite

[How To Build CodePen With React](https://www.youtube.com/watch?v=wcVxX7lu2d4)

[Stop Using Create React App](https://www.youtube.com/shorts/Xrgddey8jcA)

```bash
npm i vite@latest
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled.png)

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%201.png)

```bash
npm create vite@latest
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%202.png)

```bash
C:\laragon\www
λ cd C:\Users\naasy\Desktop\TEST LAB
```

```bash
C:\Users\naasy\Desktop\TEST LAB
λ npm create vite@latest
√ Project name: ... codepen-react
√ Select a framework: » React
√ Select a variant: » JavaScript
```

```bash
Scaffolding project in C:\Users\naasy\Desktop\TEST LAB\codepen-react...
```

```bash
Done. Now run:
```

```bash
cd codepen-react
npm install
npm run dev
```

```bash
C:\Users\naasy\Desktop\TEST LAB
λ
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%203.png)

```bash
cd codepen-react
npm install
npm run dev
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%204.png)

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%205.png)

Remove Unnnecessarry files from src directory

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%206.png)

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%207.png)

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%208.png)

[How To Build CodePen With React](https://youtu.be/wcVxX7lu2d4?t=107)

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%209.png)

src\App.jsx

```jsx
import { useState } from 'react'

function App() {
  

  return (
    "Salam"
  )
}

export default App
```

src\index.css

```css
/* cleans this */
```

src\main.jsx

```jsx
import React from 'react'
import ReactDOM from 'react-dom/client'
import App from './App'
import './index.css'

ReactDOM.createRoot(document.getElementById('root')).render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
)
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%2010.png)

index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="/vite.svg" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Vite + React</title>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.jsx"></script>
  </body>
</html>
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%2011.png)

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%2012.png)

src\elements\Logics.jsx

```jsx
import { useState } from 'react'

function Logics() {
  

  return (
    "Salam"
  )
}

export default Logics
```

src\a.css

```css
/* cleans this */
```

src\chain.jsx

```jsx
import React from 'react'
import ReactDOM from 'react-dom/client'
import Logics from './elements/Logics'
import './a.css'

ReactDOM.createRoot(document.getElementById('divStar')).render(
  <React.StrictMode>
    <Logics />
  </React.StrictMode>
)
```

index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="/vite.svg" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Vite + React</title>
  </head>
  <body>
    <div id="divStar"></div>
    <script type="module" src="/src/chain.jsx"></script>
  </body>
</html>
```

package.json

```jsx
{
  "name": "codepen-react",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  },
  "devDependencies": {
    "@types/react": "^18.0.24",
    "@types/react-dom": "^18.0.8",
    "@vitejs/plugin-react": "^2.2.0",
    "vite": "^3.2.3"
  }
}
```

vite.config.js

```jsx
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

// https://vitejs.dev/config/
export default defineConfig({
  plugins: [react()]
})
```

⬅️ ⏮️

[How To Build CodePen With React](https://youtu.be/wcVxX7lu2d4?t=190)

[CodeMirror](https://codemirror.net/)

[react-codemirror2](https://www.npmjs.com/package/react-codemirror2)

```bash
npm i codemirror react-codemirror2
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%2013.png)

[codemirror](https://www.npmjs.com/package/codemirror)

```bash
npm i codemirror
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%2014.png)

[react-codemirror2](https://www.npmjs.com/package/react-codemirror2)

```bash
npm i react-codemirror2
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%2015.png)

```bash
npm install react-codemirror2 codemirror --save
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%2016.png)

**[React Codemirror2 does not install - Stack Overflow**https://stackoverflow.com › questions › react-codemirro...](https://stackoverflow.com/questions/70903473/react-codemirror2-does-not-install)

Jan 29, 2022 — When I try to install ***react***-***codemirror2*** it gave an error and doesn't install in my app (my react version is @17.0.2) Why it doesn't install?

**[3 answers](https://stackoverflow.com/a/70904819)** · Top answer: If anyone else has the same problem like me He/she can just install "react-codemirror2-react-17" ...

***[react***-***codemirror2*** has no CSS effect](https://stackoverflow.com/questions/51826469/react-codemirror2-has-no-css-effect)

Aug 13, 2018

***[CodeMirror*** editor duplicating - javascript](https://stackoverflow.com/questions/72464452/codemirror-editor-duplicating)

Jun 1, 2022

[How to get a value from code mirror in ***react*** js?](https://stackoverflow.com/questions/72659453/how-to-get-a-value-from-code-mirror-in-react-js)

Jun 17, 2022

***[react***-***codemirror2*** creating two editors](https://stackoverflow.com/questions/73518247/react-codemirror2-creating-two-editors)

Aug 28, 2022

[More results from stackoverflow.com](https://www.google.com/search?q=react-codemirror2+site:stackoverflow.com&sxsrf=ALiCzsYZ6fFB1RpXtZGzlQURncbyFEahsg:1669432081741&sa=X&ved=2ahUKEwiAuNWR78r7AhUN1zgGHXumD2MQrQIoBHoECD0QBQ)

[React Codemirror2 does not install](https://stackoverflow.com/questions/70903473/react-codemirror2-does-not-install)

```bash
npm install react-codemirror2 --legacy-peer-deps
```

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%2017.png)

![Untitled](Build%20CodePen%20With%20React%20Js%202022%20and%20Vite%201764ee335797477eaef72ce68b79ceaf/Untitled%2018.png)

[How To Build CodePen With React](https://youtu.be/wcVxX7lu2d4?t=289)