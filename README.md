# QuestionBag
A Single Page Application built with Django, Django REST Framework and Vue JS.

This is the source code of my final year web development project.

The task was to develop a web app using different frameworks for the backend and frontend.

## How to set up the project environment to run on your local machine?

Make sure you have python3 and pip installed.

```bash
sudo apt install python3-pip
```
Confirm the pip3 installation.


```bash
pip3 --version
```


Clone / Download the project and move inside the folder.


# Create a new Python Virtual Environment:

Now install virtualenv via pip3.

```bash
pip3 install virtualenv
```

Install virtualenvwrapper via pip3:

```bash
pip3 install virtualenvwrapper
```
Once the module is installed we are ready to create virtual environments for Python 3.
```bash
python3 -m venv my-project-env
```


To start using this virtual environment, you need to activate it by running the activate script:

```bash
source my-project-env/bin/activate
```
Now install all the Python/Django dependencies:

```bash
pip install -r requirements.txt
```

## Usage
# Move inside the QuestionBag folder and apply the migrations : 

```python
cd QuestionBag
python manage.py makemigrations
python manage.py migrate
```
# Install the Vue JS dependencies: 

```bash
cd QuestionBag/frontend
npm install
```
# Run Vue JS Development Server:
```bash
npm run serve
```

# Open a new terminal and run Django's development server:

```bash
python manage.py runserver
```
# Open up your browser and go to 127.0.0.1:8000
![home](https://user-images.githubusercontent.com/55706752/71542147-79f8ca80-2928-11ea-8033-3324ae444da3.PNG)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
