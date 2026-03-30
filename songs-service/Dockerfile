# Smaller OS footprint using JRE
FROM amazoncorretto:21
WORKDIR /app

ADD build/libs/*.jar /app/app.jar
#COPY wait-for-db.sh /app/wait-for-db.sh
#RUN chmod +x /app/wait-for-db.sh
#ENTRYPOINT ["/app/wait-for-db.sh"]

CMD ["java", "-jar", "app.jar"]