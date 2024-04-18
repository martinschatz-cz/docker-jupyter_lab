`docker build -t custom_julab:test . --no-cache`

`docker run -it --rm -p 10000:8888 custom_julab:test`

`docker run -it --rm -p 10000:8888 -e PASSWORD=password custom_julab:test`
