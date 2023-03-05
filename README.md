# CCPI
### how to add your project
in your project add a `ccpi.json` file
```json 
{
  "version"{
    "major":0,
    "minor":0
  },
  "requirements":[
    "ccpi"
  ],
  "files":{
    "main":"your main file"
  }
}
```
then make a pull request adding `"your project name":"raw link to your repo"` to `index.json`
eg.
```json
{
  "ccpi":"https://raw.githubusercontent.com/badgeminer/ccpi/main/"
}
```
