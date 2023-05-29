# Elm static site generator (template)
This template is based on this guide
https://korban.net/elm/elmstatic/
## How to run template
### 1. Install dependancies
```bash
sudo npm install -g elmstatic
```
```bash
sudo npm install -g http-server
```
```bash
npm install 
```
### 2. Build site 
```bash
elmstatic build
```
### 3. Run http-server
```bash
cd _site
```
```bash
http-server
```
## How to setup without template?
### 1. Install dependancies
```bash
sudo npm install -g elmstatic
```
```bash
sudo npm install -g http-server
```
```bash
sudo npm install -g browser-sync 
```
### 2. Create project
- create empty directory and navigate into it
```bash
mkdir example
cd example
```
- initialize project
```bash
elmstatic init
```
### 3. Modify and run template 
- build files with
```bash
elmstatic build
```
- run http-server
```bash
cd _site
```
```bash
http-server
```
- For live reload run
```bash
elmstatic watch
```
### 4. Want more detailed guide?
https://korban.net/elm/elmstatic/

