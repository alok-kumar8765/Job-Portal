## Django Job Portal
Online Job portal Project in Python Django with source code. This web application is to be conceived in its current form as a dynamic site-requiring constant updates both from the seekers as well as the companies.
The objective of the project is to enable jobseekers to place their resumes and find appropriate jobs while companies to publish their vacancies and find good candidates.
It enables jobseekers to post their resume, look for jobs, view personal job listings. It will provide various companies to put their vacancy profile on the location and even have an choice to search candidate resumes.
Apart from job-seekers and Companies(Job Provider) there'll be an admin module to manage complete Portal also as jobseeker and corporations .

# Online Jop Portal Features
Administrator
Job Seeker
Job Provider
Job Search
System Users
Administrator
Job Seeker
Job Provider

# ADMINISTRATOR FEATURES
## Administrator can manage whole website:

Manage complete jobseeker section. Like: activate/deactivate/delete/ edit jobseeker’s information.
Admin user can view the jobseeker’s applications for each job.
Manage complete employer section. Admin user can activate/deactivate/delete/ edit company information.
Manage posted jobs. Like: activate/deactivate/delete/edit posted job.
Manage whole website content. Dynamic CMS is included to manage the content of the website.
Admin user can send message to any jobseeker or job provider.
Admin user can send bulk emails as well.
Admin user can manage the skills section. Like: Add or remove skills from the website.
Manage newsletters section
Manage success stories
Admin user can manage and handle the prohibited words for whole website.
Admin user can add/edit countries, cities, salaries range, qualification, institutes, job industries, website ads.

# JOB PROVIDER / COMPANY FEATURES
## After registration job provider can perform following action:
Add / Edit company’s profile
Post new job vacancies
Edit / Deactivate posted jobs
Job provider can see the list of jobseekers who has applied for the job
Job provider can search jobseekers
Job provider can see and download the jobseeker’s resume
Job provider can send message to any job seeker

# JOB SEEKER FEATURES
## After registration job seeker can perform following actions:

Search for jobs
Apply Online for desire job
Add/Edit profile information including qualification, experience, and skills.
Build his resume by using CV builder functionality of the website.
Upload latest resume.
MAIN WEBSITE(WEBSITE FONT END)
From main website, user can perform following actions:

Search jobs on the basis of skills, city, country or job title
Register as a jobseeker or as a job provider
Login to jobseeker or job provider portal
About Us
Contact us
Recent Jobs
Local environment Install

Clone the repository and install the packages in the virtual env:pip install -r requirements.txt
Add .env file.cp .env.dev.sample .env
Add Github client ID and client secret in the .env file
Run
1.With the venv activate it, execute:

python manage.py collectstatic
Note : Collect static is not necessary when debug is True (in dev mode)

# Create initial database:python manage.py migrate
# Load demo data (optional):python manage.py loaddata fixtures/app_name_initial_data.json – app app.model_name
# Run server:python manage.py runserver
# Run test:
# python manage.py test

# To dump data:
python manage.py dumpdata – format=json – indent 4 app_name > app_name/fixtures/app_name_initial_data.json


#### An open source online job portal.

Live: [Demo](https://django-portal.herokuapp.com/)

Used Tech Stack

1. Django
2. Sqlite

### Screenshots

## Home page
<img src="screenshots/one.png" height="800">

## Add new position as employer
<img src="screenshots/two.png" height="800">

## Job details
<img src="screenshots/three.png" height="800">

Show your support by 🌟 the project!!