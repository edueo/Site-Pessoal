build:
	JEKYLL_ENV=production jekyll build

dev:
	jekyll serve

static:
	rsync -azv --exclude "Makefile" _site/* /data/repos/github.com/edueo/edueo.github.io
