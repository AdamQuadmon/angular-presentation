# AngularJS: how we SAP!

This presentation is made upon [Reveal.js](https://github.com/hakimel/reveal.js)

This work is deeply inspired to [Dan Wahlin](https://twitter.com/DanWahlin) fabulous talk [AngularJS Fundamentals In 60-ish Minutes](http://www.youtube.com/watch?feature=player_embedded&v=i9MHigUZKEM).

## Installation

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all reveal.js features as well as the development tasks needed to make changes to the source.

### Basic setup

You'll simply need to download a copy of this repository and open the index.html file directly in your browser.g


### Full setup

Some reveal.js features, like external markdown, require that presentations run from a local web server.
The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone this repository
```
$ git clone git@github.com:AdamQuadmon/angular-presentation.git
```

5. Install dependencies
```
$ npm install
```

6. Serve the presentation and monitor source files for changes
```
$ grunt serve
```

7. Open <http://localhost:8000> to view your presentation


### Folder Structure
- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)



##  Reveal.js License

MIT licensed

Copyright (C) 2013 Hakim El Hattab, http://hakim.se