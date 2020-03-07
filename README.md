### **Flixter Yoga Project**


This Flixter Yoga Web application includes a video streaming platform, featuring credit card payment capabilities, user role management, complex user interfaces, and advanced database relationships.

I created the web application using ruby, ruby on rails framework, HTML, CSS, javascript, and bootstrap.

I set up the files such as MVC. (Models, View, Controllers)



> Main Page


<img width="1149" alt="Screen Shot 2020-03-06 at 6 28 44 PM" src="https://user-images.githubusercontent.com/43684968/76135208-bbb58980-5fd9-11ea-9f54-e33abb58652c.png">

<img width="1198" alt="Screen Shot 2020-03-06 at 6 29 06 PM" src="https://user-images.githubusercontent.com/43684968/76135209-beb07a00-5fd9-11ea-9809-a44a62666222.png">


> Sign in, Sign up Page

I integrated with the bootstrap gem and simple_form gem since this web application needs user authentication for sign in and sign out then I add user authentication with devise. 

<img width="1266" alt="Screen Shot 2020-03-06 at 6 29 53 PM" src="https://user-images.githubusercontent.com/43684968/76135247-f1f30900-5fd9-11ea-8420-251a56a18ddd.png">


> Courses Page

Each course includes a number of sections (groupings of videos) and each section includes a number of video lessons. Thus, the database structure for sections, which the grouping of videos.

<img width="1198" alt="Screen Shot 2020-03-06 at 6 29 26 PM" src="https://user-images.githubusercontent.com/43684968/76135237-e9023780-5fd9-11ea-857a-77fc7e180c59.png">



<img width="1219" alt="Screen Shot 2020-03-06 at 6 30 37 PM" src="https://user-images.githubusercontent.com/43684968/76135117-fec32d00-5fd8-11ea-8920-541f7bac3f79.png">


> Credit Card Payment  

This web application requires users to be enrolled in a course to view the lessons, thus I ensure that only authenticated users are able to view the lesson show page, by adding the devise gem to the gemfile.



<img width="859" alt="Screen Shot 2020-03-06 at 6 31 11 PM" src="https://user-images.githubusercontent.com/43684968/76135116-fbc83c80-5fd8-11ea-8dc9-6e5f6f4edfbd.png">


If a user attempts to view the lesson detail page for a course they are not enrolled in, they should be redirected back to the course detail page with an error message indicating that they must enroll before viewing the lesson.



