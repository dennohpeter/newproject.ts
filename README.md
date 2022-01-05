# newproject.js
This is a script for helping you automate creating new projects, currently supports typescript projects

#### Why?
I created a node script recently to automate one workflow that I do repeatedly. Everytime I create a new Typescript project, I'd create

1. src/index.ts
2. .prettierrc file and add 4 configurations i.e 
```
{
 "semi": true,
 "singleQuote": true,
 "tabWidth": 2,
 "useTabs": false,
}
```

3. custom package.json with author name, author email

