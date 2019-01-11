FROM        [image:tag]             #Repo download
MAINTAINER  [Author     <email>]    #Author tag
COPY        [SRC][DST]              #Needed from host to guest
ADD         [SRC][DST]              #mirip $COPY
USER        [UID|UNAME]             #Default User
WORKDIR     [PATH]                  #Default Workdir
VOLUME      [PATH]                  #Default MountPointFS
EXPOSE      [PORT/PROTO<tcp|udp>]   #Tunnel for outside Communication

RUN         [COMMAND]               #Default Command when compiling image
CMD         [COMMAND]               #Default Command when image compiled
ENTRYPOINT  [COMMAND]               #Default Command make docker like executable