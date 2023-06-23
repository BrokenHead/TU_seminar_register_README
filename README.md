# TU Seminar register (Web App)

http://203.131.211.59/
This site was built using git hub pages [login DEMO](https://brokenhead.github.io/TU_seminar_register_README/login_TU_SEMINAR_.html).

## What the project does
(planned stable version of TU Web Seminar Register)

v1
- user(Thammasat's Employee) can view own Seminar and Training program
- user can record own Seminar and Training by themself but it not verify
- can print sorted seminar to summary PDF file

v2
- admin management in application
- can register admin by open ticket or adding manually
- auto genarate letter of consent for organization director/dean to accept organization admin
  
- admin can view relevant user Seminar
- admin can print relevant user's seminar (PDF file)
- admin can record seminar to relevant user
- admin can edit record who's under relevant


###  Why the project is useful
- make HR admin got less call phone for checking who's passing Seminar and Training
- make facility admin can register Seminar by themself not have to pass Seminar data to HR admin
- user can register Seminar record by themself and all Seminar and register printout same form 


### How users can get started with the project
- go to .....//Seminar_register or use it from HR TU web

### Where users can get help with your project
contact me Varist
- call 2564 4440 to 1898 (home telephone Thailand)
- +66 62-535-9519 
- Varist.siri@gmail.com

### Who maintains and contributes to the project
- make and maintains by Varist Siriumpunkul Thammasat University's Computer Technical Officer.


## devloper guide line

First, go to VM that is hosting this program (http://203.131.211.59/)

- open Command Prompt and cd to folder : D:\web_node_js\TU_seminar_register
```
  cd D:\web_node_js\TU_seminar_register
```

- open VS code and run nodemon for open server (by the way if this program is running normally that mean this web server is run as startup run time service)
```
  code .
```
```
  npm run dev
```


## Installation notation

!!!!!! because database now we use oracle 10g for prevend error
WE MUST USE 
- oracledb version 5.5.0 (less than version 6.0.0)

## this program is testing and running on stack
### Front-End
- ejs version : 3.1.8
### Back-end
- express : 4.18.1
- node js -v : v18.16.0
### Database
- oracle 10g

other
- npm -v : 9.5.1
- Windows Server 2022 Standard version : 21H2


