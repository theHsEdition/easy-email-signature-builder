# Easy-peasy Python Email Signature Builder

A Signature Builder for people who hate repetative tasks. I understand "easy peasy" could have alot of different interpretations, but in this case, I will walk you throught how to use everything, so it really shouldn't be that hard.

## CSV
You can convert any Excel document or Google Sheet doc into a csv. Put in header labels in your document, here's what mine look like:

- fname
- lname
- email
- ...

## Python
A quick script that will convert a `.csv` to `.md` files

- Open up the terminal program...
- Type `cd ~/yourprojectfolder` to change directory to your pythonpractice folder, and hit Enter. (A cool trick is to type `cd` and then drag the folder into the terminal window and then hit Enter.)
- Type `python _csv_to_jekyll.py` to run your program!

## Jekyll
A ruby-based static-site generator we're going to use to make html files. Compiles the Markdown files into html files.

- Open up the terminal program...
- Type `cd ~/yourprojectfolder` and hit Enter.
- Type `jekyll run` and the jekyll server should start right up in the terminal.
- Your html files should have generated like magic in the "site" folder

### Thanks to these guys for setting the groudwork for some of my code

- https://kinlane.github.io/github-micro-tool-yaml/
- https://github.com/hfionte/csv_to_yaml