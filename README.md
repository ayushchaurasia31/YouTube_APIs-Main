# YouTube_APIs-Main
An API to fetch latest videos from youtube sorted in reverse chronological order of their publishing date-time from YouTube for a given tag/search query in a paginated response.

The server fetches latest videos async after every 10 minutes and saves it to the db.

This project is completely based on Django.

# Method Used
Used Cron Jobs django_cron to fetch videos after every 10 minutes using Youtube Data Api and save it to the db

# Setup Guide
Clone the project
As this project is based on Django, your system need to have proper python setup, refer this
Go the project through the terminal and install all dependencies by using typing pip install -r requirements.txt in the terminal
Inside the setting.py file, fill the variable GOOGLE_API_KEYS with all the API Keys available,the list should be filled as ['API_KEY_1','API_KEY_2',...]
For getting an API key follow this
Setup crontab to run Job, Follow this
Run the server using python mange.py runserver
# Screenshots
For visualization through a dashboard one may directly run the app locally and the get the UI provided through django-rest-framework
# Dashboard
<img width="1440" alt="dashboard" src="https://user-images.githubusercontent.com/46618132/141683079-c7cdf3d5-ffab-43a9-bba2-d97b17e66dc9.png">
# Filters
<img width="1435" alt="filters" src="https://user-images.githubusercontent.com/46618132/141683085-d82b055a-ca84-4ab2-9eb0-40f566b59de3.png">
