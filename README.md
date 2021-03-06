js-empty
========

An empty client side JavaScript project.
It can be cloned to form the base of 
other JavaScript projects.

## Initial Dependencies

1. [nodejs][nodejs] and in particular npm.
2. [Google Chrome][gchrome]. 

It is recommended that [nvm][nvm] be used to manage node versions,
although this is not neccessary.

It is possible to use any browser to run tests, but Google Chrome
has been set as the default because it integrates well with 
[Jetbrains][jetbrains] IDEs like [WebStorm][webstorm], [RubyMine][rubymine]
and [IntelliJ][intellij] for integrated debugging via the 
[JetBrains IDE Support extension][jbidesupport].


## Setup

1. Get a copy of the project:

        git clone https://github.com/andybry/js-empty
        
2. Rename the project to suite you. e.g:

        mv js-empty my-project

3. Enter the project. e.g. 

        cd my-project

4. Make sure [karma][karma] is available on the system:

        npm install -g karma-cli

5. Install node modules:

        npm install


## Usage

After setup unit tests (in the spec folder) can be continually run (on change)
against the JavaScript that you write (in the js) folder:

        karma start

A modular approach to JavaScript is recommended with one module per file and
one test suite (in its own file) for each module. The testing framework 
is [Jasmine][jasmine].

<!-- References -->
[nodejs]: http://nodejs.org/
[nvm]: https://github.com/creationix/nvm
[gchrome]: http://www.google.co.uk/intl/en_uk/chrome/browser/
[jetbrains]: http://www.jetbrains.com/
[webstorm]: http://www.jetbrains.com/webstorm/
[rubymine]: http://www.jetbrains.com/ruby/
[intellij]: http://www.jetbrains.com/idea/
[jbidesupport]: https://chrome.google.com/webstore/detail/jetbrains-ide-support/hmhgeddbohgjknpmjagkdomcpobmllji
[karma]: http://karma-runner.github.io/0.12/index.html
[jasmine]: http://jasmine.github.io/