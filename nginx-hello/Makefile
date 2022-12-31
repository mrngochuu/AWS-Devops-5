install:
	#clone hadolint
	wget -O ./hadolint https://github.com/hadolint/hadolint/releases/download/v1.16.3/hadolint-Linux-x86_64 &&\
    #access permission
	chmod +x ./hadolint
	#install html_linter
	pip install html_linter
lint:
	# run lint
	./hadolint Dockerfile
	html_lint.py index.html