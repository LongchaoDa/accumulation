# This is the Longchao's accumulation Doc related to Research

### update methods:
1. Modify content in ./source/content 
2. Go to root path `./` and execute `make clean` to clean the previous html file
3. Stay at root path `./` and execute `make html` to transfer from .md file to html file, target folder is in `./build/html`
4. Cd `./build/html` and copy the content and overwrite the content in root `./`, make sure `index.html` is exposed directly in `root`.
5. Update the content with `git add .`,`git commit -m 'xxx'` and `git push`.