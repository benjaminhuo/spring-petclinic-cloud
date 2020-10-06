VERSION ?= v0.8.0
IMG ?= benjaminhuo/opentelemetry-javaagent-all:$(VERSION)

docker:
		docker build -t ${IMG} .
		docker push ${IMG}