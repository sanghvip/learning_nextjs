# learning_mern
A repository for recording notes while learning next js
creating backend
1. npm init - created a new node project for us


2. since we are using typescript, we have to install types packages. nodemon gives us development server
the above libs are only dev libs. This will help us improve our performance in the production by reducing the libs in our build package.

3. named vs default export: only one default export can be present but there can be multiple named export. Named exports are basically used to export mutliple utilities from the module.
[reference link](https://stackoverflow.com/questions/36795819/when-should-i-use-curly-braces-for-es6-import)


4. we are going to use vite for developing front end. we wil be usin typescript+swc . SWC is basically a typescript and javascript compiler written in rust to provide faster compile times as compared to bable.

5. one can override styles in tailwind by adding that class name in the tailwind config file

6.interfaces in typescript - [link](https://www.typescriptlang.org/docs/handbook/interfaces.html)

7. beginners guide to react queries - [link](https://refine.dev/blog/react-query-guide/#mutating-data)

8. what is tsconfig.json - The tsconfig. json file is used to configure TypeScript projects, similar to how package. json is for JavaScript projects. The tsconfig.json generated by Create React App will resemble the following: tsconfig.json.

9. Can we add comments to json -  The short answer is no. The JSON specification does not include comments, and they cannot be used in JSON files (i.e. files with a . json extension). Comments were removed from the JSON specification to prevent developers from using them to specify parser directives, which complicated the data format.
