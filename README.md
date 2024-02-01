# UniMate-V2

UniMate-V2 was a substantial project that not only exempted me from the practical exam of the Data Structures course during my second year of college but also served as the basis for my Object-Oriented Programming practical exam. The decision to use C++ and the QT framework was motivated by the requirements of the latter course.

The project originated from the need to replace our old college e-learning portal, which was being phased out in favor of a new system.

## Features
The application, built using the QT framework, emulates an e-learning portal, providing functionality for both students and professors. 

### Student Features
- View enrolled courses
- Choose a major and enroll in relevant courses
- Access information about professors, courses and ECTS points

### Professor Features
- View students enrolled in their courses
- Access information about students
- Choose majors to teach and specific courses within those majors

## Implementation
The project involved the implementation of linked lists from scratch to demonstrate a solid understanding of data structures. The data structure used was a tree of linked lists, with the main list representing "Majors." Each major node contained linked lists of "Courses," and each course node contained lists of professors and students.

The login/register screen interacted with local directories on the laptop to save and retrieve data. Upon login, the program instantiated a tree of linked lists based on the local data. 

When a user logged in, the program determined whether they were a professor or a student and opened the corresponding panel. Professors had the ability to select majors and courses to teach, while students could choose their majors and enroll in relevant courses.

It's worth noting that, at the time of development, I did not utilize any version control system. The project was managed through local saves, which, coupled with the use of Google Drive and multiple PCs, led to some data loss.

Upon program closure, the entire data structure was deallocated.
