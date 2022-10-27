version: 2
jobs:
build:
docker:
- image: circleci/ruby:242
steps:
- checkout
- run: "A first hello"
