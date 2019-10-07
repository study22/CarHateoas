FROM openjdk:8
COPY . /usr/src/myapp #copies all files into this path into the container
WORKDIR /usr/src/myapp #within the container
RUN javac src/main/java/com/sunny/CarhaeteosApplication.java
CMD ["java", "CarhaeteosApplication"]