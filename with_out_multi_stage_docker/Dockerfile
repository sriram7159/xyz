
# picking a base image for this
FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update \
 && apt-get install -y --no-install-recommends openjdk-17-jdk \
 && rm -rf /var/lib/apt/lists/*


 WORKDIR  /tarak1


 COPY Main.java .


 RUN javac Main.java

 CMD ["java","Main"]