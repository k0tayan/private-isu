all: app

app: *.go go.mod go.sum
	orchestrion go build -o app
	sudo mv app /usr/local/bin/app
	sudo chmod +x /usr/local/bin/app