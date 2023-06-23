# TU Seminar register (Web App)
serve view, register and printing PDF of personal seminar data with admin system and admin management include auto genarate letter of consent document


http://203.131.211.59/
This site was built using git hub pages [login DEMO](https://brokenhead.github.io/TU_seminar_register_README/login_TU_SEMINAR_.html).

##  Why the project is useful
### - seminar data PDF print out will summarize time and data of sorted seminar to use in pay rise, contract renewal or rise academic position in same form
- user can register Seminar record by themself
- make HR admin got less call phone for checking who's passing Seminar and Training
- make facility admin can register Seminar by themself not have to pass Seminar data to HR admin


## What the project does
(planned stable version of TU Web Seminar Register)

v1
- user(Thammasat's Employee) can view own Seminar and Training program (verified by HR of Thammasat University)![image](https://github.com/BrokenHead/TU_seminar_register_README/assets/37082529/49d46b18-1a55-45a5-9120-24ac4198829e =250x250)
- user can record own Seminar and Training by themself but user mush verify seminar by themself![image](https://github.com/BrokenHead/TU_seminar_register_README/assets/37082529/27dc98a5-eb1a-487e-a8c5-8fe9cea00853)
- can print sorted seminar to summary's PDF file![image](https://github.com/BrokenHead/TU_seminar_register_README/assets/37082529/9f1d7d39-8720-4125-a7dd-34eda8485310)

v2
- admin management in application
- can register admin by open ticket or adding manually
- auto genarate letter of consent for organization director/dean to accept organization admin
  
- admin can view relevant user's Seminar
- admin can print relevant user's seminar (PDF file)
- admin can record seminar to relevant user
- admin can edit record who's under relevant


### Where system admin can get help with this project
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


