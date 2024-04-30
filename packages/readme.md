export GH_USERNAME='orjands*
export GH_TOKEN='auth code'
GH_IMAGE_NAME='hello-world'
export GH_VER='1.0.0'
export TAG_NAME='ghrc.io/$GH_USERNAME/$GH_IMAHE_NAME:$GH_VERS'

echo $GH_TOKEN | docker login ghrc.io -u $GH_USERNAME --password-stdin

docker tag hello-world:latest $TAG_NAME

docker push $TAG_NAME
