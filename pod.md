בנית image
docker build -t test11:v1 .

הרצת דוקר
docker run --name ariel -d test11:v1
docker run --name ariel -p 8080:8080 -d test11:v1


בניה ועליה לגיטהב(במקום בפקודה הקודמת)
docker buildx build -t arielizralevitch/test11 --push .

