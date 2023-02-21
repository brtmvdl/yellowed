FROM circleci/android:api-30-node

WORKDIR /app

COPY app .

RUN ./gradlew build

CMD ls -la ./app/build
