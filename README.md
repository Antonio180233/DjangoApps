"# DjangoSocialApp" 
This is an application similar(Generic) to any social media that may exist, you can create users, you can make publications, you can delete the user's publications in turn, you can edit profiles, add profile images, you cannot like or make comments, but thats up to you all up to you, if you want to use this.

Due to time, it still has some bugs, but the potential of the project for the application of the analytics is very wide, suggesting people to follow could be a great recommendation system, or sugesting boks

For local operation follow the next steps

1-Clone the repository or download it as zip.

2-Create a virtual environment python -m venv socialenv

3-Install the dependencies/libraries in requirements.txt pip install -r requirements.txt

4-Run the migrations. python manage.py makemigrations python manage.py migrate

5-Create a superuser. python manage.py createsuperuser

name email password

6- The app is ready to be launched in Azure, you just have to adjust the parameters of the DB, the allowed host, generate a file with the password since I put an  os get method instead of a string with the password, if you want to try this locally you gotta modify all this by following the Django docummentation, changing the Db parameters to the sqlite ones and the local host too.
