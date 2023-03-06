# CCPI
## ![](https://raw.githubusercontent.com/badgeminer/ccpi/main/pkg-removebg-preview.png) packaging for cc:tweaked
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
then make a pull request adding a file named `"your project".json` with
```json
{
  "url":"raw link to your repo"
}
```
