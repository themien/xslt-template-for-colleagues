# Preparation

1. Open this folder in [VSCode](https://code.visualstudio.com/)

2. Add this to your settings.json

   - open settings.json (if you don't know how: https://stackoverflow.com/a/65909052/12737316)

   ```json
   "[xslt]": {
    "editor.defaultFormatter": "deltaxml.xslt-xpath",
    "editor.formatOnSave": true,
    "editor.semanticHighlighting.enabled": true,
    "editor.formatOnSave": true
   }
   ```

3. Install these extensions:

   - https://marketplace.visualstudio.com/items?itemName=deltaxml.xslt-xpath
   - https://marketplace.visualstudio.com/items?itemName=deltaxml.html-preview

4. Make sure you have node installed.
   - open terminal and type `node --version` if you see something like `v17.0.1` everything is good.
   - if not then:
     - on Mac and Linux get [brew](https://brew.sh/) (again to check if you have it run `brew --version`) and then run `brew install node`.
     - on Windows get [chocolatey](https://community.chocolatey.org/) (again to check if you have it run `choco --version`) and do `choco install nodejs`

That's it!

# Usage

1. put xml data files inside `/data` folder
2. put xsl files inside `/src` folder
3. call corresponding xsl file the same as the xml data file
4. use `CMD + SHIFT + B` to run an xsl file
   - on windows do `CTRL + SHIFT + B`
5. right click `result.html` and click "Open Preview"
