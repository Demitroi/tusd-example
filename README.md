# tusd-example
Example using [MinIO](https://min.io/) as Amazon S3 Object Storage, [tusd](https://github.com/tus/tusd) as Server Implementation of tus: the open protocol for resumable file uploads https://tus.io/ and [Uppy](https://uppy.io/) as Frontend. All running on [Docker](https://www.docker.com/)

1. Start the services
```
$ docker-compose up -d
```

2. Open http://127.0.0.1:9000 in the browser
![1.jpg](images/1.jpg)

3. Login with the default credentials that are in the ```docker-compose.yaml``` file
![2.jpg](images/2.jpg)

4. Create a bucket called ```mybucket```
![3.jpg](images/3.jpg)
![4.jpg](images/4.jpg)

5. Open http://127.0.0.1:9506/ in the browser
![5.jpg](images/5.jpg)

6. Upload any file
![6.jpg](images/6.jpg)

7. Check that the file has been uploaded
![7.jpg](images/7.jpg)