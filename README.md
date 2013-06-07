Sublime Text 2 Setup
====================

### Sublime Text 2 Setup Instructions

**Step 1:**
*Install Package Manager*

Hit Ctrl + ` to open the console

**Paste:**

	`import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print('Please restart Sublime Text to finish installation')`
	
**Step 2:**
*Install Plugins*

* Emmet
* SideBar Enhancements


**Step 3:**
*Install Theme*

