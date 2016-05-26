#SAS Package for Sublime Text

A modest package for doing SAS programming. [Read all about it here.](http://implementing-vdw.blogspot.com/2012/10/new-sublime-text-package-available-for.html)

Installation is via git only right now.  In your [packages folder](http://docs.sublimetext.info/en/latest/basic_concepts.html#the-packages-directory):

```
git clone git://github.com/rpardee/sas.tmbundle.git SAS
```

Or failing that, [download the package as a zip from github](https://github.com/rpardee/sas.tmbundle/zipball/master) and then unzip it into %PACKAGES%/SAS.

I am now developing in Sublime Text 3 beta, though I believe everything works in ST2.

#To-Do
1. Polish build system.
  1. Fix error/warning check.
  2. (Possible?) Bring ST3 to the fore upon completion of a job.
2. Make installable via [Package Control](http://wbond.net/sublime_packages/package_control).  (Subject to Package Control's compatibility w/ST3.)
3. Polish syntax definition.
4. Add a menu item to allow quick access to SAS.sublime-settings
