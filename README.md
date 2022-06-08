# Build and Deploy a React Admin Dashboard App With Theming, Tables, Charts, Calendar, Kanban and More

## Link:

```sh
    https://amazing-admin-dashboard.netlify.app/
```

#Set up

1. Delete src folder and newly create it again as a empty folder and add file called App.js and index.js.

2. just copy paste- package.json

```sh
   {
   "name": "project_syncfusion_dashboard",
   "version": "0.1.0",
   "private": true,
   "dependencies": {
   "@syncfusion/ej2": "^19.4.48",
   "@syncfusion/ej2-react-calendars": "^19.4.48",
   "@syncfusion/ej2-react-charts": "^19.4.50",
   "@syncfusion/ej2-react-dropdowns": "^19.4.52",
   "@syncfusion/ej2-react-grids": "^19.4.50",
   "@syncfusion/ej2-react-inputs": "^19.4.52",
   "@syncfusion/ej2-react-kanban": "^19.4.48",
   "@syncfusion/ej2-react-popups": "^19.4.52",
   "@syncfusion/ej2-react-richtexteditor": "^19.4.50",
   "@syncfusion/ej2-react-schedule": "^19.4.50",
   "react": "^17.0.2",
   "react-dom": "^17.0.2",
   "react-icons": "^4.3.1",
   "react-router-dom": "^6.2.1",
   "react-scripts": "5.0.0"
   },
   "scripts": {
   "start": "react-scripts start",
   "build": "react-scripts build",
   "test": "react-scripts test",
   "eject": "react-scripts eject"
   },
   "eslintConfig": {
   "extends": [
   "react-app",
   "react-app/jest"
   ]
   },
   "browserslist": {
   "production": [
   ">0.2%",
   "not dead",
   "not op_mini all"
   ],
   "development": [
   "last 1 chrome version",
   "last 1 firefox version",
   "last 1 safari version"
   ]
   },
   "devDependencies": {
   "autoprefixer": "^10.4.2",
   "eslint": "^8.9.0",
   "eslint-config-airbnb": "^19.0.4",
   "eslint-plugin-import": "^2.25.4",
   "eslint-plugin-jsx-a11y": "^6.5.1",
   "eslint-plugin-react": "^7.28.0",
   "eslint-plugin-react-hooks": "^4.3.0",
   "postcss": "^8.4.6",
   "tailwindcss": "^3.0.19"
   }
   }
```

3. And then install all the dependecies

```sh
    npm install --legacy-peer-deps
```

4. then create files called App.css and index.css.
5. then create 2 files in main project called craco.config.js and tailwind.config.js just copy paste it, what it is in my project.
