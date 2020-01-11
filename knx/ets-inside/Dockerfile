FROM debian:9
RUN export DEBIAN_FRONTEND=noninteractive && apt-get update
RUN export DEBIAN_FRONTEND=noninteractive && apt-get upgrade
RUN export DEBIAN_FRONTEND=noninteractive && apt-get install -y apt-utils libc6-dev libunwind8 ibssl1.0.2 icu-devtools
EXPOSE 8081
CMD cd /opt/KNX/ETSInside; /opt/KNX/ETSInside/Knx.Ets.Osprey
