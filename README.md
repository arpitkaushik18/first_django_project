# Discussion forum

Here, I have tried to create a forum to start discussion on different topics.

## Getting Started

These are the following step to achive the goal:-

### Prerequisites

Things which you need to install before actually starting the project - 

```
python 3.6
virtial environment
django 1.11.4
```

### Installing Part

* Open Terminal ```(Ctrl+Alt+T)``` and run the following commands one by one - 

1) If you are using Ubuntu 16.04 or an older version, first add the following repository : 

```sudo add-apt-repository ppa:deadsnakes/ppa```

2) Install python 3.6 :

```sudo apt-get update```<br>
```sudo apt-get install python3.6```

3) Installing Virtualenv :

* First install <b>pip</b> for our Python 3.6.2 version - <br>
```wget https://bootstrap.pypa.io/get-pip.py```<br>
```sudo python3.6 get-pip.py```

* Now install <b>virtualenv</b> :

```sudo pip3.6 install virtualenv```


## Start the Project

* Now, we are ready to start our first project on django.

* Make a folder in which we will store our files and things related to django project, including virtual environment.

```mkdir myproject```<br>
```cd myproject```

* Now, start virtual environment and install django :

```virtualenv venv -p python3.6```<br>
```source venv/bin/activate```<br><br>
```pip install django```

#### Next Step :

### Download all the files and folders and keep inside the already created <b>myproject</b> folder.

* Now, run the following command : 

```python manage.py runserver```

#### And, to see the result paste the following URL in your browser :

```http://127.0.0.1:8000```

### Press ```Ctrl+C``` to close the running server

### Now, create an Administrater account by running the following command and providing useful info : 

```python manage.py createsuperuser```

#### Now, open the URL in your web browser : 

```http://127.0.0.1:8000/admin/```

### Now, your work is done. Make your own changes to see how it works.

## Acknowledgments

* My work is a brief version of a similar project from [https://simpleisbetterthancomplex.com/series/2017/09/11/a-complete-beginners-guide-to-django-part-2.html]

