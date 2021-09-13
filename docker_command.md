1. 도커 이미지 확인 
`docker images`

2. 도커 이미지 삭제
`docker rmi <imageId>`

3. 도커 이미지 전체 삭제.
`docker rm -f $(docker ps -aq)`

4. 도커 in 도커는 권장하지 않는다. 뿐만 아니라 실행이 안된다.

FYI : https://aidanbae.github.io/code/docker/dinddood/