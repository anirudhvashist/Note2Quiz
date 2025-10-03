
### package.json
```json
{
  "name": "note2quiz",
  "version": "1.0.0",
  "description": "AI-powered quiz application for children",
  "main": "src/index.js",
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js",
    "build": "webpack --mode production"
  },
  "dependencies": {
    "express": "^4.18.0",
    "mongoose": "^7.0.0",
    "openai": "^3.0.0",
    "react": "^18.0.0",
    "react-dom": "^18.0.0"
  },
  "devDependencies": {
    "nodemon": "^2.0.0",
    "webpack": "^5.0.0"
  },
  "keywords": ["education", "quiz", "ai", "children", "learning"],
  "author": "Your Name",
  "license": "MIT"
}
