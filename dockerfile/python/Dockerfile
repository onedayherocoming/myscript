FROM python


RUN export http_proxy=http://172.17.0.1:7890 && apt update && apt install -y tmux vim git

WORKDIR /workspace