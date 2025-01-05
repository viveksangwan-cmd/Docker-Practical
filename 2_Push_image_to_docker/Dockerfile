# Instructions to build, tag, and push the image:
# 1. Build the image:
#    docker build -t your_image_name .
# 2. Log in to Docker:
#    docker login
# 3. Tag the image:
#    docker tag your_image_name your_dockerhub_username/your_image_name
# 4. Push the image:
#    docker push your_dockerhub_username/your_image_name

FROM nginx
COPY ./index.html /usr/share/nginx/html