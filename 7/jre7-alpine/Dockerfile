FROM tomcat:7-alpine

MAINTAINER planet3tu

ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8
ENV TZ "Asia/Shanghai"

USER root
ADD deploy-and-run.sh bin/
RUN chmod +x bin/deploy-and-run.sh
VOLUME ["/usr/local/tomcat/"]

CMD ["bin/deploy-and-run.sh"]