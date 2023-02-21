FROM circleci/android:api-30-node

WORKDIR /app

COPY app .

RUN ./gradlew build --scan

# RUN ./gradlew assembleDebug --scan

CMD ls -la ./app/build
