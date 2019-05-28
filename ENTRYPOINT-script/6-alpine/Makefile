VERSION = 6-alpine
IMAGE = ofstudio/node:$(VERSION)

all: image publish
	
image:
	docker build -t $(IMAGE) --no-cache .

publish:
	docker push $(IMAGE)
