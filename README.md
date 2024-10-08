
# Person Detection and Counting using YOLOv8, Supervision, and Flask

This project is a comprehensive solution for real-time person detection and counting, utilizing the powerful YOLOv8 model, enhanced with Supervision for post-processing and analytics, and providing a user-friendly web interface through Flask.

![demo (3)](https://github.com/user-attachments/assets/8b3be4ee-5b96-4093-9f0c-9eb11800b580)

## Documentation
You can check the YOLOv8 documentation 
[here](https://www.bing.com/ck/a?!&&p=6a4393ad5d2e03e2JmltdHM9MTcyNDgwMzIwMCZpZ3VpZD0yZWY4NzI3OS03YWM2LTZlNmEtMmMyOC02MDQ4N2JkYzZmMzAmaW5zaWQ9NTIwMw&ptn=3&ver=2&hsh=3&fclid=2ef87279-7ac6-6e6a-2c28-60487bdc6f30&psq=ultralytics&u=a1aHR0cHM6Ly9kb2NzLnVsdHJhbHl0aWNzLmNvbS8&ntb=1).


## Deployment

Clone the project

```bash
  git clone https://github.com/kamel-werhani/Person-Detection-and-Counting-using-YOLOv8-Supervision-and-Flask.git
```

Go to the project directory

```bash
$ cd Person-Detection-and-Counting-using-YOLOv8-Supervision-and-Flask
```

Install dependencies

```bash
$ pip install -r requirements
```

Start the server

```bash
$ python .\flaskapp_counting.py
```
## Deployment on docker Container
1. Build the Docker image using Dockerfile.
```bash
$ docker build -t docker-image-name .

```
2. Run the Docker Container
```bash
$ docker run -d -p 5000:5000 docker-image-name

```
