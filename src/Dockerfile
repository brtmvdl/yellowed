FROM circleci/android:api-30-node

WORKDIR /app

COPY app .

RUN export JAVA_HOME="$( dirname $( which javac ) )"

RUN sudo ./gradlew clean build --no-build-cache

# RUN ./gradlew assembleDebug --scan

CMD ls -la ./app/build
