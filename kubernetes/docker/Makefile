.DEFAULT=build

IMAGE=timwebster9/locust-k8s

build:
	docker build -t ${IMAGE} .

up:
	docker-compose down && docker-compose up

down:
	docker-compose down

push: build
	docker push ${IMAGE}