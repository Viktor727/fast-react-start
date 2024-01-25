
1. "# fast-react-start" 

npm create vite@latest
npm install
npm install @mui/material @emotion/react @emotion/styled
npm install create-react-component-folder

2. Need to put this one to package.json: 
"crcf": [
    "typescript",
    "scss"
  ]


3. Need to put this one to package.json to scripts:
"cc": "npx crcf src/components/PostList -f"
