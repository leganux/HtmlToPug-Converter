# HtmlToPug-Converter
*html template converter to templates with pug as view engine*

Set a folder where the files to be found will be to be the input directory, so set a folder for the output files 

Example of directory paths to enter:
- Input directory : /home/mike98/Desktop/html_files
- Output Directory : /home/mike98/Desktop/pug_files

---
# Install

```
git clone https://github.com/Miguel98R/HtmlToPug-Convertidor.git
```

```
npm install
```

```
npm run dev
```


Then visit http://localhost:3008/*


*By default start on port 3008 , this can be modified in the index.js file

---
# Initializing template converted

Once you have converted the template, you will notice that a structure has been created for your project ,
an api-rest based on js express and a database connection in mongo db, this to help in the process of creating projects

Converted views to pug are located in the views folder and static/library files are located in the public folder

to initialize the project simply install the node modules and run the dev command


```
npm install
```

```
npm run dev
```
The project to be launched on port 3055 , this can be modified in the index.js in its defined sallida folder
Then visit http://localhost:3055/*


**Mike Rosas 2023. - HtmlToPug-Convertidor v1.0.0  - developed by: Jose Miguel Rosas Jimenez**
