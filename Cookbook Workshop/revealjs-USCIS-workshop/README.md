## Purpose
This [reveal.js](https://github.com/hakimel/reveal.js/) presentation is meant to supplement a class I am teaching at Chef Rally 2017 (Internal Chef Conference). It covers the following:

  - Integrating Compliance with Chef Server/Automate
  - [The Audit Cookbook](https://github.com/chef-cookbooks/audit)
  - InSpec Code Plugins for Atom/VS Code

## How to View

### Basic Viewing

Download a copy of this repository and open the index.html file directly in your browser.

### Full Viewing (Not Required)

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

  1. Install [Node.js](http://nodejs.org/) (4.0.0 or later)
  2. Clone this repository
  3. Install dependencies
     ```sh
     $ npm install
     ```
  4. Serve the presentation and monitor source files for changes
     ```sh
     $ npm start
     ```
  5. Open <http://localhost:8000> to view your presentation
     > You can change the port by using `npm start -- --port 8001`.
