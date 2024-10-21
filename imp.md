npm- node package manager 
npx -  node package executer

npx create-react-app--> npm run start // this is a bulky method it takes lots of time 
so nowadays its recommended to use vite and parcel
npm create vite@latest
npm install 
npm run dev

react  is the core libe and in this there are 2 lib one is react do for web developemnt and react native for app 
"web-vitals": "^2.1.4" --> track performance 


"scripts": {
    "start": "react-scripts start", --> development environment mai projects ko chalana ke liye 
    "build": "react-scripts build",--> build convert react into js becoz browser ko htmlcss js hi samajh ataa hai 
    "test": "react-scripts test", -->test case run karne ke liye 
    "eject": "react-scripts eject" --> react ko eject karne ke liye agar hamaar kaam ho jataa hai aur hume dusra framework/lib use karna hai to 



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
  }
}
--> it tells broswer version