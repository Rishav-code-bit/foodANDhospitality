# foodANDhospitality
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Rishav%20Kumar-red)
---
## SCREENSHOTS
### Home Page
![dashboard snap](https://user-images.githubusercontent.com/75771591/157800542-8a1db62c-9d33-460e-ac5a-c007d1ce4dbb.png)
### Admin Dashboard Dark theme
![dashboard snap](https://user-images.githubusercontent.com/75771591/157800621-2a4c9e9a-cda1-49e7-b721-e55f8c6f6b6d.png)
### Admin Dashboard Light theme
![dashboard snap](https://user-images.githubusercontent.com/75771591/157800736-c29af952-451a-4c95-a978-999d37d3d3ad.png)
### Volunteer Dashboard
![dashboard snap](https://user-images.githubusercontent.com/75771591/157800800-1add0847-93fb-4a35-b5f9-fac12c9c0c5f.png)
### Informer Dashboard
![dashboard snap](https://user-images.githubusercontent.com/75771591/157800867-3fd1f52e-041a-4afe-9274-e4332afa424a.png)
---
## FUNCTIONS
## Informer
- informer will signup and login into system
- informer can make request for service of their vehicle by providing details.
- After Request approved by admin, informer can check budget, status of service
- informer can delete request (Enquiry) if customer change their mind or not approved by admin (ONLY PENDING REQUEST CAN BE DELETED )
- informer can check status of Request(Enquiry) that is Pending, Approved, worked-on, Done
- informer can check invoice details
- informer can send feedback to admin
- informer can see/edit their profile
---
## Volunteer
- volunteer will apply for job by providing details like (skills, address, mobile etc.)
- Admin will hire(approve) volunteer account based on skill
- After account approval, volunteer can login into system
- volunteer can see how many work (states to work-on) is assigned to me
- volunteer can change status of service according to work progress
- volunteer can see salary and how many vehicles he/she have repaired so far
- volunteer can send feedback to admin
- volunteer can see/edit their profile
---
### Admin
- First admin will login ( for username/password run following command in cmd )
```
py manage.py createsuperuser
```
- Give username, email, password and your admin account will be created.
- After login , admin can see how many informer, volunteer, recent service orders on dashboard
- Admin can see/add/update/delete informers
- Admin can see each informer invoice (if two request made by same customer it will show total sum of both request)
- Admin can see/add/update/delete volunteers
- Admin can approve(hire) volunteers (requested by mechanic) based on their skills
- Admin can see/update volunteer salary
- Admin can see/update/delete request/enquiry for service sent by informer
- Admin can also make request for service (suppose customer directly reached to service center/office)
- Admin can see all service cost of request (both approved and pending)
- Admin can see feedbacks sent by informer/volunteer
---
### Other Features
- we can change theme of website day(white) and night(black)
- if customer is deleted by admin then their request(Enquiry) will be deleted automatically

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
pip install django==3.0.5
pip install django-widget-tweaks

```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```


## Feedback
Any suggestion and feedback is welcome. You can message me on facebook
- [Contact on Linkedin](https://www.linkedin.com/in/rishavkumar-)
