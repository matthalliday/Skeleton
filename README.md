What is Fortress?
=================
Fortress is a custom-tailored project skeleton for creating lightweight, semantic websites.

It's pretty barebones, so it won't be for everyone. If other templates, boilerplates or frameworks didn't quite work out for you, then you might appreciate this one.

Instructions
------------
The default setup will be suitable for most people, but making customizations is easy too. If you change the `assets` directory structure, be sure to update the relative paths found in `index.html` and `Guardfile`.

1. Install dependencies using `bundle install`
2. Compile Sass & Coffeescript files with `bundle exec guard`
3. (Optional) Enable the LiveReload browser extension to automatically refresh the page when files are saved

It is recommended that you keep `Gemfile` & `Guardfile` in your project's root directory and also check them into version control. This will ensure that every team member has the same configuration.

Acknowledgements
----------------
Thanks to everyone involved with [HTML5 Boilerplate](http://html5boilerplate.com). It's a fantastic project made by people way smarter than me. This project wouldn't exist without all your hard work.

Also, the fine folks behind [The Sass Way](http://thesassway.com) for writing an awesome function to translate pixels into ems and for the rest of your amazing articles.

Contributing
------------
1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request