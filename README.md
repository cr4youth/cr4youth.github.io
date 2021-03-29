# cr4youth.org
Equipping and empowering youth and young adults to overcome adversity and challenges.

# About
## Technologies used:
1. Javascript
2. HTML
3. SCSS/CSS
4. Bootstrap 5
5. [Themesberg Pixel Bootstral UI Kit](https://github.com/themesberg/pixel-bootstrap-ui-kit)

## Get started
### pre-reqs:
1. install NodeJs
2. install gulp
3. install git

### Set up application for development
1. clone repository 
   `git clone https://github.com/cr4youth/cr4youth.org.git`
2. cd into `cr4youth.org` folder 
   `cd cr4youth.org`
3. run npm install to install dependencies 
   `npm install`
4. run `gulp` to run the server 
   `gulp`
5. the browser should pop up, but if it does not, open the browser and browse to http://localhost:3000
6. when changes are made to the source code, the browser will refresh

## To deploy
Once the application is in a satisfactory state, build and deploy:
1. `gulp build:dist`
2. commit all changes via 
   `git commit -m "short note about what was updated"`
3. push changes to `main` branch 
   `git push origin main`
4. this site is hosted on GitHub Pages through the `dist` folder, so, GitHub Pages should pick everything up!

