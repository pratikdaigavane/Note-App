# Note-App
A Command line note app based on node.js


## Instructions
The entry point of this app is **app.js**. 
Run the script in the format `node app.js  [command] [options]`.
The commands that are currently supported are:
- `add`
  - Adds a note.
  - Parameters need are `--title` and `--body`. 
  - Example: `node app.js add --title="title goes here" --body="body goes here"`
- `list`
  - All the notes are listed.
  - No parameters are needed. 
  - Example: `node app.js list`
- `read`
  - Reads a note.
  - Parameter need is `--title`. 
  - Example: `node app.js read --title="title goes here"`.
- `remove`
  - Removes a note.
  - Parameter need is `--title`. 
  - Example: `node app.js remove --title="title goes here"`.
  
  
  
 ### Remarks
   - You can also use `-t` instead of `--title` and `-b` instead of `--body`.
   - `node app.js --help` gives you all available commands and options.
   - All the dependencies are listed in `package.json`.
