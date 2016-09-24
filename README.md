# Alexander
An example Semantic UI portfolio website.

[Live preview](http://alexander.earth23.com/)

## Requirements
* Node.js with npm
(see [Installing Node.js](https://nodejs.org/en/download/package-manager/))
* Gulp (`npm install -g gulp`)

## Setup

```bash
# Clone the repository via SSH
git clone git@github.com:ybaras/alexander.git
#Or HTTPS
git clone https://github.com/ybaras/alexander.git

# Enter the project's directory
cd alexander

# Install Semantic UI dependencies
npm install
```
Use gulp to build the .js and .css files
```bash
# Enter the semantic directory
cd semantic

# Build all files
gulp build

```
### Build tools

Semantic UI will configure itself using an install script built into the package.
After setup you can use gulp to build your project's css:
```bash
# Enter the semantic directory
cd semantic

# Build all files
gulp build

# Watch files
gulp watch
```
