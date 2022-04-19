
all: build deploy

build:
	cargo build-bpf --bpf-out-dir=dist/program

deploy: 
	solana program deploy dist/program/helloworld.so
