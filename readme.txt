# Tools needed:
Chrome / Firefox
VScode
VScode extensions: 
    1) HTML CSS Support 
    2) CSS Peek 
    3) Prettier: turn on format on save
    4) Highlight Matching Tag
    5) Todo Highlight
    6) Live server

JS library for animation
    1) AOS animation (google it)


Resources
1: google html validator    
2: google css validator


#Build for production
Build Tools 
- Webpack: so many configuration
- Parcel: zero configuration --> good for beginners 
    - Install node
    - npm init -y (-y option to skip questions) --> generate package.json
    - npm i -D parcel-bundler (i: install, -D)
    - npm_modules/.bin/parcel index.html (use parcel to launch our app)
        - or: npm i -g parcel-bundler (to install parcel globally)
        - then: parcel index.html
    - parcel build index.html (build for production)
        - I encounted a tree.render error. Check "https://stackoverflow.com/questions/67087634/parcel-js-tree-render-is-not-a-function" for solution

# Deployment
Providers
- Netlify: able to connect to github directly


