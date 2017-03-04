# phpstorm-reactjs
ReactJS Live templates for PHPStorm

### How to:

1. Download [settings.jar](raw/master/settings.jar) file
1. Click `File` -> `Importing Settings...` on your IDE menu, select `settings.jar`, then click `OK`.

#### Manually insert template file
1. [Download](raw/master/template/ReactJS.xml) and copy the *xml* file(s) to your templates folder:

    * Windows: `<your home directory>\.<product name><version number>\config\templates`
    * Linux: `~\.<product name><version number>\config\templates`
    * OS X: `~/Library/Preferences/<product name><version number>/templates`

    e.g. `~/Library/Preferences/WebIde80/templates` on OS X for PhpStorm 8

1. Restart PhpStorm.

1. To see all templates, go to *Preferences->Live Templates* and expand the Template Group.

It's hard to remember shortcuts when there are a large number of options. A more efficient way is to take advantage of PhpStorm's *Insert Live Template* shortcut. Press `Cmd + J` and type as many letters as you want to filter the resulates.

For example, to create a new ReactJS class, type `rcc` and press Tab or press `Cmd + J` and write `rcc` or `React` 
