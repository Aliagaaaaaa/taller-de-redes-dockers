FROM ubuntu:latest
RUN apt-get update && apt-get install -y vlc x11-apps
RUN useradd -ms /bin/bash vlcuser
ENV DISPLAY=:0
USER vlcuser
CMD ["vlc"]
