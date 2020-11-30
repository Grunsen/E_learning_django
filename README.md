# E_learning_django
This is the E-learning platform with Content Management System (CMS).

Course Models:

Subject 1
    Course 1
        Module 1
            Content 1 (image)
            Content 2 (text)
        Module 2
            Content 3 (image)
            Content 4 (text)
            Content 5 (video)
…


I was aiming for the next functionality:
Login to the CMS
List the courses created by the instructor
Create, edit and delete courses
Add modules to a course and reorder them
Add different types of content to each module and reorder them
List all available courses for students, optianly filtered by subject
Display a single course overview
Using Django cache framework and monitoring the Memcached cache backend
Build a RESTful API for project

By using model inheritance, I created a versatile system to manage different types of content for the course modules. I implemented a custom model field to order objects. I also discovered how to use class-based views and mixins. I used formsets to manage course modules, and built a drag-and-drop functionality with jQuery UI to reorder modules and their contents. I created serializers and views for models and built custom API views. I also added authentication to API and restricted access to API views using permissions. I used the Requests library to consume the API from an external Python script.
