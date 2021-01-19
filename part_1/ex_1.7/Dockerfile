FROM ubuntu:16.04
WORKDIR /mydir 
COPY scriptfile.sh .
RUN apt-get update && apt-get install -y curl
CMD ["/bin/bash", "scriptfile.sh"]


