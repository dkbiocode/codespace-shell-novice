
default: 02-files-directories.html

%.html: %.md
	pandoc $^ --embed-resources --standalone --from markdown --to html5 -o $@
