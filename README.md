# Design Thinking Template

Contributors: Richard Knights, Jonathan Lazarini, James Nash, Ben Oakenfull & Marcos Peebles

+ Team involved in specific project
+ Add Stanford and Ideo creds
+ Add html5up and pixelarity creds
+ humans.txt

## Usage

Each HTML file is generated from mustache temples and their respective json files.
Scaffold has been extended from Call Me Nick work.

### Templates

* `index.mustache` - home page (full screen slider) template

### Data files

* `index.json` - data file for `index.mustache`

### Scripts

* `npm run build` - compiles all templates
* `npm run deploy` - Will require AWS credentials and having them exported in your shell

## License

Licensed under the MIT license, [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)

Copyright 2014, Call Me Nick
[http://callmenick.com](http://callmenick.com)

## Improvements
- Add scripts for processing scss, livereload
- Add script to compile sass
- Implement pipeline