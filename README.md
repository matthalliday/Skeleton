# What is Fortress?
Fortress is a custom-tailored project skeleton for creating lightweight, responsive, & accessible websites.

It's pretty barebones, so it won't be for everyone. If other templates, boilerplates or frameworks didn't quite work out for you, then you might appreciate this one.

## Features
### Lightweight
- Makes minimal HTTP requests
- Loads scripts at the bottom of the page
- Compiles Sass using the compressed style

### Responsive
- Adjusts the site to the device width
- Allows people to pinch or tap to zoom

### Accessible
- Keyboard navigable
- Skip to content link
- Uses HTML5 section elements & ARIA landmark roles

## Instructions
The default setup will be suitable for most people, but making customizations is easy too. If you change the `assets` directory structure, be sure to update the relative paths found in `index.html` & `package.json`.

1. Install [Node.js](https://nodejs.org/). The latest stable version is recommended (currently 7.5.0).
2. Run `npm install` to get all dependencies (currently just node-sass).
3. Run `npm run build` to compile Sass & watch for changes.

## Acknowledgements
Thanks to everyone involved with [HTML5 Boilerplate](http://html5boilerplate.com). It's a fantastic project made by people way smarter than me. This project wouldn't exist without all your hard work.

Also, the fine folks behind [The Sass Way](http://thesassway.com) for writing an awesome function to translate pixels into ems & for the rest of your amazing articles.

## Contributing
1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
