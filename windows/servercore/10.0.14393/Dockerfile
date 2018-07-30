FROM microsoft/nanoserver
ENV WINDOWS_IMAGE_VERSION=sac2016

RUN mkdir C:\BuildAgent
WORKDIR C:/BuildAgent
COPY ./Start.* ./

CMD ["Start.cmd"]