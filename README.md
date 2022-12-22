# oop_project #
**#About the project**
This project has been prepared as a term project within the scope of Ceng213 Object Oriented Programming (OOP) course.This project is a multi-layered system of departments that includes lecturers, staff, students, courses and areas in the department.
This project aims to present a perspective on Gazi University Computer Engineering Department.


When we examine the project in detail , generally; lecturers are identified by their name and surname, id number and the courses they teach. In addition to the lecturers, there are other staff whose job descriptions are specified in terms of the sustainability of the functioning of the department.
On the other hand, there is a student part of the project. It is defined whether the students graduated or not. In addition, each student's ID number, name - surname information, the courses s(he) took and the grade information of these courses were added.Degree information of graduate students is also given. 
Course code, name, credit and location information of the courses given in the department are defined. The information of the instructor giving the course and the ID number of the student taking the course are also available in the system.
In addition to these, social areas and classes where lessons are given have also been created.

**#A micro scale of the technical details of the project**
 The project went through the following stages in general during the construction phase: (1) Defining the common properties of objects using class structures (class), defining object properties and methods that handle objects within these structures, (2) Creating objects using defined classes, solving problems with these objects.
At first glance, we see several related classes. An instance of a public class:

![Ekran görüntüsü_20221222_124323](https://user-images.githubusercontent.com/121099203/209106523-bebc4e03-af5c-4659-8adb-0ecc4d4ecb6b.png)

A hierarchy was established between the related classes with the help of the inheritance principle. In this way, duplicating the codes is avoided. Here is a small example of it:

![Ekran görüntüsü_2022127822_121856](https://user-images.githubusercontent.com/121099203/209103121-209e5d44-a094-480f-ae90-28449d998db8.png)

At the same time, abstract classes were created too which means a restricted class that cannot be used to create objects. Abstract methods are also defined in abstract classes. As these methods do not contain body, only method definitions have been made and overrided. Below we see an example of an abstract (super) class made for 'student':


![Ekran görüntüsü_20221222_132728](https://user-images.githubusercontent.com/121099203/209114877-ecbd6995-d932-4049-b12c-5d3c822b6853.png)


And again in connection with this, we see an overridden abstract method:


![Ekran görüntüsü_20221222_133607](https://user-images.githubusercontent.com/121099203/209117245-eead0759-0056-40d3-a72b-26e140909c5f.png)



Apart from these, some extra methods have been defined to strengthen the project and make it more understandable. An example of an extra method designed for this:

![Ekran görüntüsü_20221222_134928](https://user-images.githubusercontent.com/121099203/209119132-d29f6929-185c-4c0f-b02a-e2afec898013.png)












