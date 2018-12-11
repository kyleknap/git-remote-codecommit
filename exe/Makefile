all: exe

exe:
	rm -rf ./dist/git_remote_codecommit
	rm -rf ./build/git_remote_codecommit
	pyinstaller --onefile git-remote-codecommit.spec && echo "helper exe built"
