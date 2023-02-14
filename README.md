## About this

Some Days I am trying to send a mail with google authentication, I want to send a mail with google auth token.
I am unable to find any package for that. as a result I am starting to create a new project for this.
I have flowing some of the steps to create this project as flows.

### step 1: Create google cloud platform project

you can get [help](https://cloud.google.com/resource-manager/docs/creating-managing-projects) to create a google cloud platform project

### step 2: Enable gmail api

you can find Gmail API from serch options then click to enable buton then go to credentials and find

1. API Keys
2. OAuth 2.0 Client IDs
3. Service Account

### step 3: Configure OAuth Consent

You can also find OAuth consent screen and click External Radio and click CREATE button
filup all information with appropriate data then click SAVE AND CONTINUE button
and flow this other steps and if filup all information then BACK TO DASHBAORD

### step 4: Create OAuth Client ID

go to credentials and click to create credentials button and click OAuth client ID
a) select Web application
b) provide application name
c) provide authorized redirect URls (http://127.0.0.1:8000/get-token)
then click to create button

now you can find
Client ID 92600441827**_
Client secret GOCSPX_**
Creation date February 14, 2023 at 1:25:05 PM GMT+6

### step 5: Configure Laravel Project

1. you need ot install [PHPMailer](https://github.com/qalbit/laravel-phpmailer-google-oauth) package
2. you need to install [oauth2-google](https://github.com/thephpleague/oauth2-google) package

### step 6: Configure routes and blades files

### step 7: Manage OAuth Controllers

### step 8: Publish OAuth App

### step 9: Connect OAuth App
