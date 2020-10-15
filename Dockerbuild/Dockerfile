FROM rocm/pytorch:latest
MAINTAINER Lucas Manchine <lucasperinm@gmail.com>

RUN apt-get update -y

RUN python3.6 -m pip install --upgrade pip \
    && python3.6 -m pip install fastai \
    && python3.6 -m pip install --upgrade nbdev \
    && python3.6 -m pip install --upgrade jupyter

RUN python3.6 -m pip install --upgrade python-dotenv

WORKDIR /files

CMD ["jupyter", "notebook", "--allow-root", "--port=1337", "--ip=0.0.0.0"]
