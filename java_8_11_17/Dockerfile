FROM chesnay/flink-ci:base

RUN wget -q https://github.com/adoptium/temurin17-binaries/releases/download/jdk-17.0.1%2B12/OpenJDK17U-jdk_x64_linux_hotspot_17.0.1_12.tar.gz

RUN tar -C /usr/lib/jvm -xzf OpenJDK17U-jdk_x64_linux_hotspot_17.0.1_12.tar.gz

RUN echo "JAVA_HOME_17_X64=/usr/lib/jvm/jdk-17.0.1+12" >> /etc/environment

ENV JAVA_HOME_17_X64 "/usr/lib/jvm/jdk-17.0.1+12"