## Tips:

* Sometimes you may choose to ignore certain errors that flake8 will throw, [here](http://flake8.pycqa.org/en/latest/user/ignoring-errors.html) is a good resource on ignoring them. 
	* Cliffs note version, end a line like this 
   
		```
		example = lambda: 'example'  # noqa
		```

* You can also version control the configuration for flake8 by adding a .flake8 file to the root of your project, here's a sample

	```
	[flake8]
	ignore = D203
	exclude = .git,__pycache__,docs/source/conf.py,old,build,dist
	max-complexity = 10
	```

