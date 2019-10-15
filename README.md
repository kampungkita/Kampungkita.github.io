# Kampungkita.github.io
Kampung Kita - Github Pages
./
├── .editorconfig
├── Gruntfile.js
├── package.json
├── bower.json
├── README.md
├── CHANGELOG.md
├── Rakefile
├── Gemfile
├── _config.yml
├── post.sh
├──grunt/                                      * grunt tasks
|   ├── task.js
│   └── aliases.yml 
|
├── dev/                                       * site source
|   ├── coffee/                                * coffee scripts
|	│   └── main/                              * main scripts
|	│
│   ├── images/                                * image sources
|	│
│   ├── jade/                                  * templates
|	|	├── blocks/                            * blocks library
|	│   |   └── block.jade
|	│   ├── helpers/                           * helper mixins
|	│   ├── vendor/                            * third-party code
|	│   ├── layouts/                           * page layouts
|	│   └── pages/                             * main pages templates
|	│
│   ├── js/                                    * compiled and source js
|	|   ├── main/                              * main site scripts
|	│   ├── ie/                                * ie compat scripts
|	│   └── vendor/                            * vendor scripts
|	│
|	├── sass/                                  * sass preprocessor styles
|	|	├── blocks/                            * blocks library
|	│   |   └── block.sass
|	│   ├── helpers/                           * mixins and vars
|	│   ├── vendor/                            * third-party code
|	│   └── screen.sass
|	│
│   ├── ruby/                                  * jekyll plugins
|	│
│   ├── helpers/                               * helper files
|	│
│   ├── fonts/                                 * font sources
|	│
│   └── devtools/                              * some dev tools
│
├── build/                                     * built source
|	├── index.html
|	├── _data/                                 * jekyll data (i18n, locales)
|	|
|	├── _drafts/                               * drafts
|	|
|	├── _layouts/                              * layouts for jekyll generation
|	|
|	├── _plugins/                              * jekyll plugins
|	|
|	├── _posts/                                * posts (*.md)
|	|
|	└── static/                                * static assets
|		├── css/                               * minified styles
|		|
|		├── images/                            * minified images
|		│
|		├── js/                                * minified assembled js
|		|
|		└── fonts/                             * @font-face-ready webfonts
│
└── publ/                                      * generated website
	├── _data/                                 * jekyll data (i18n, locales)
	|
	├── _drafts/                               * drafts
	|
	├── _posts/                                * posts (*.md)
	|
	└── static/                                * static assets
		└── images/                            * post and pages images
