# randomfacts_app
Hosting on Python Anywhere

<p align="center">
  <img src="img.PNG" alt="My Random Fact App" />
</p>


- Sign up for PythonAnywhere, you'll be taken to your dashboard.
- Find the link near the top right to your "Account" page.
- Select the tab named "API token", and hit the button that says "Create new API token".
- Go backto Dashboard by clicking on the logo, and choose the option to start a "Bash" console.

  ```
	pip3.10 install --user pythonanywhere
	pa_autoconfigure_django.py --python=3.10 https://github.com/abuu94/randomfacts_app.git
	python manage.py createsuperuser

- Your site should now be live on the public Internet! Click through to the PythonAnywhere "Web" page to get a link to it.
- You can share this with anyone you want. :)
