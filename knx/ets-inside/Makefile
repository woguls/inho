.DEFAULT_GOAL := all

all: build run

build:
	docker build -t ets-inside-debian .

run:
	docker run --mount src=/opt/KNX/ETSInside,target=/opt/KNX/ETSInside,type=bind   -it  -p 8081:8081 ets-inside-debian
