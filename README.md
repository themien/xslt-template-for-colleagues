# Preparation

1. Add this to your settings.json

   ```json
   "[xslt]": {
    "editor.defaultFormatter": "deltaxml.xslt-xpath",
    "editor.formatOnSave": true,
    "editor.semanticHighlighting.enabled": true,
    "editor.formatOnSave": true
   }
   ```

2. Install these extensions:

   - https://marketplace.visualstudio.com/items?itemName=deltaxml.xslt-xpath
   - https://marketplace.visualstudio.com/items?itemName=deltaxml.html-preview

3. Make sure you have node installed.
   - open terminal and type `node --version` if you see something like `v17.0.1` everything is good.
   - if not then the best way is to get brew (again to check if you have it run brew --version) and then run `brew install node`.

That's it!

# Usage

1. put xml data files inside /data folder
2. put xsl files inside /src folder
3. call corresponding xsl file the same as the xml data file
4. use `CMD + SHIFT + B` to run an xsl file
