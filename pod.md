בנית image
docker build -t test11:v1 .

הרצת דוקר
docker run --name ariel -d test11:v1
docker run --name ariel -p 8000:8000 -d test11:v1


בניה ועליה לגיטהב(במקום בפקודה הקודמת)
docker buildx build -t arielizralevitch/test11 --push .

The purpose of this pod is to be the wrapper for the container I built in docker hub.