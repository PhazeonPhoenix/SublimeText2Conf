# Sublime Text 2 Settings #
My custom configurations for Sublime Text 2. Probably not much use for anyone
else.

## Usage ##
1. Install / Extract [Sublime Text 2](http://www.sublimetext.com/2).
2. Launch Sublime Text 2 and install [Sublime Package Control](http://wbond.net/sublime_packages/package_control).

  ```import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print 'Please restart Sublime Text to finish installation'```
5. Close Sublime Text 2.
7. Browse to package directory.
6. Delete existing User directory.
7. Clone this repo as the User directory.
8. Launch Sublime Text 2 again.
9. Ignore any error messages about missing themes or palettes.
9. Wait for Sublime Package Control to download and install all packages.
10. Restart for good measure.
