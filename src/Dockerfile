FROM circleci/android:api-30-node

WORKDIR /app

COPY app .

ENV JAVA_HOME /usr/local/openjdk-11/bin

RUN sudo ./gradlew clean build --no-build-cache

# RUN ./gradlew assembleDebug --scan

CMD ls -la ./app/build
