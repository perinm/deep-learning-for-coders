FROM rocm/pytorch:latest
MAINTAINER Lucas Manchine <lucasperinm@gmail.com>

RUN apt-get update -y

COPY requirements.txt /tmp

RUN python3.6 -m pip install --upgrade pip \
    && python3.6 -m pip install --upgrade --force-reinstall -r /tmp/requirements.txt
#    && python3.6 -m pip install --upgrade fastai fastcore nbdev jupyter python-dotenv
#    && python3.6 -m pip install --upgrade nbdev \
#    && python3.6 -m pip install --upgrade jupyter

#RUN python3.6 -m pip install --upgrade python-dotenv

WORKDIR /files

CMD ["jupyter", "notebook", "--allow-root", "--port=1337", "--ip=0.0.0.0"]
