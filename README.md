# deep-learning-for-coders
In this repo I publish my answers to the exercises on the "Deep Learning for Coders" book, by Jeremy Howard, founder of Fast.ai

Meetings info:
https://trello.com/b/SOgQILab/fastai-2020-2-semestre/calendar/2020/11

Link for the book:
https://www.amazon.com.br/Deep-Learning-Coders-fastai-PyTorch/dp/1492045527

# Instructions for rocm configuration on docker

Install docker, docker-compose in your machine.

Download:
- https://github.com/perinm/deep-learning-for-coders/blob/master/docker-compose.yml
- https://github.com/perinm/deep-learning-for-coders/tree/master/Dockerbuild/*

On the same folder as your docker-compose.yml file, run:

```
sudo docker-compose up --build
```

Edit docker-compose.yml and change volumes acoordingly to the folders you want to use.

Currently is using my folder called 'notebooks'.
