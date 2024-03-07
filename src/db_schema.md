# Database Schema

Here, you can explore the database schema employed to organize all important data concerning the project. As you can see the schema comprises of 5 tables. They all are connected via foreign keys. The entire system is structured around the central table, `User`, as it serves as the main element. This strategic design ensures that user data is stored in the most optimal manner for accessibility and efficiency. Additional information related to users is organized within tables such as `PassRequest`, `CourseRequest`, `Donation`, and `ElectiveCourse`.

![db_schema](prisma-erd.svg)