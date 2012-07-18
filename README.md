## Requirements:
* ruby 1.9.2+
* [activesupport](https://rubygems.org/gems/activesupport)
* [trollop](https://rubygems.org/gems/trollop)

Usage: `4pcbr$ processing c my_awesome_app -m p2d -p /Users/4pcbr/workspace/Processing`

This command will create MyAwesomeApp sketch in /Users/4pcbr/workspace/Processing folder and will initialize a new git repository inside.

## Options:
* --mode, -m ( string ):   Video mode, default is opengl, available modes: opengl, p2d, p3d (default: opengl)
* --fps, -s ( integer ):   Sketch rendering fps (default: 60)
* --width, -w ( integer ):   Sketch screen width, default is 0 means fill all the screen (default: 0)
* --height, -h ( integer ):   Sketch screen height, default is 0 means fill all the screen (default: 0)
* --path, -p ( string ):   Sketch work folder, current is default
* --force, -f:   Skip prompt steps
* --git, -g:   Initialize git repository (default: true)

