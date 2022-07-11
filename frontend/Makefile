version: '3.3'
custom:
	docker build -f Dockerfile.dev .
run:
	docker run -p 3000:3000 decf12c108cefe7df4e00a78a7216
volume: 
	docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app bb053db80fd4303513ed67e52dcdb5d8592ce91dd2f13b9f97fb7adc691cd174
test:
	docker exec -it 1252524192f2 sh

.PHONY: custom run volume test