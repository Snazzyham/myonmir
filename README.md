# Project Myonmir 

At Percolate Galactic, we don't really have a build system. For most projects we just use the cli's provided to us, such as `vue-cli` or `create-react-app`, but for quick and one off projects we just end up writing pure html and css and adding features such as autoprefixer as we need it later on, and just importing pre-minified css files when we need them. 

Project Myonmir changes this. It is our first build system, and is a very minimal one. 

It is based on Webpack, because that's what the cool kids are using these days. It imports Tachyons, but as raw source files, giving us the flexibility to modify it as we need. 
