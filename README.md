# cs231n-docker
Docker container for cs231n Stanford course

Build command: docker build -t deeplearning:cs231n -f Dockerfile.gpu .
Run: nvidia-docker run -it -p 8888:8888 deeplearning:cs231n
