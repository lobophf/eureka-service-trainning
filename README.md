./gradlew :eureka-service:bootRun


./gradlew :eureka-client:bootRun --args='--server.port=8885'
./gradlew :eureka-client:bootRun --args='--server.port=8886'
