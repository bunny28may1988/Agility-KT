FROM tomcat:latest
RUN apt-get update && apt-get install curl -y 
HEALTHCHECK --interval=20s --retries=5 --timeout=30s --start-period=5s CMD curl -I -f "http://localhost" || exit 1
EXPOSE 8080
