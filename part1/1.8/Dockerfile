FROM ubuntu:18.04
WORKDIR /usr/local/bin
RUN apt-get -qq update && apt-get install -y -qq --no-install-recommends curl
CMD echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;
