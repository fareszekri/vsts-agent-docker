FROM microsoft/nanoserver
ENV WINDOWS_IMAGE_VERSION=sac2016

RUN mkdir C:\BuildAgent
WORKDIR C:/BuildAgent
COPY ./Start.* ./installChocolatey.ps1 ./
ENV chocolateyUseWindowsCompression=false
RUN @powershell installChocolatey.ps1 

CMD ["Start.cmd"]