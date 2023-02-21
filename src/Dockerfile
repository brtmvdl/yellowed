FROM circleci/android:api-30-node

WORKDIR /app

COPY app .

RUN gradlew clean build --no-build-cache

# RUN ./gradlew assembleDebug --scan

CMD ls -la ./app/build
