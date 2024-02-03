This is a copy of the official [TypeScript React app template](https://github.com/facebook/create-react-app/tree/main/packages/cra-template-typescript). 

To [create your own React app template](https://create-react-app.dev/docs/custom-templates/), clone this repository and make your edits. Convention is to name your template starting with `cra-template-*`.

To use the new template, run the following command:
```
npx create-react-app my-app --template file:../path/to/your/template/cra-template-[template-name]
```
To create a tar.gz file for distributing over the web:
```
tar -czvf template-name.tar.gz template-name
```

To use the tar.gz file as a template:
```
npx create-react-app my-app --template https://example.com/my-custom-template-0.8.2.tar.gz
```
To use a template hosted on Github, replace `blob` in the URL path with `raw`:
```
npx create-react-app my_app --template https://github.com/jtmuller5/cra-template-template/raw/main/cra-template-template.tar.gz
```
