## Spring boot, Oauth2, Social LogIn

Build Spring boot with google social login module.

## Requirements

01) Java 1.8 +
02) Maven 3.8 +
03) GCP account (Google Cloud Platform)

## Project setup

01) Clone the project

		git clone https://github.com/himash79/Spring-boot-with-social-login-google.git

02) Configure the GCP

		Follow the steps of `Set up GCP user.txt` file for configure the cloud enviroment.

03) Clean and build the project using maven

		open command line (CMD) in project directory and execute 'mvn clean install'
		
04) Open project using intelij / eclipse
		
## Expose Rest APIs

01) Authenticate user using related end-point APIs.

01) localhost:8090/ - redirect to google signIn page.
02) localhost:8090/user - redirect to logged user details.
