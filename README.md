# Deploy React приложения на GitHub
Налашування
1) зайти на сайт https://www.npmjs.com/package/gh-pages
2) в термінале встановити команду npm install gh-pages --save-dev
3) в файле package.json під строкою version додаємо ссилку (дивитися відео)
4) під строкою script додаємо дві команди
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build",
5) в терміналі додаємо команду npm run deploy
