FROM qwertytech/java:17
WORKDIR /server
COPY paper-1.18.1-216.jar .
COPY start /bin/
RUN chmod +x /bin/start
RUN echo eula=true > eula.txt
EXPOSE 25565:25565
