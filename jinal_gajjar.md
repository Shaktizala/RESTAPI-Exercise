RESOURCES : TEACHER, STUDENT, MARKS

1. TEACHER 
{
    teacher-name:"a"
    subject:"maths"
}

2. STUDENT 
{
    stu-name:"x"
    enroll:"1"
}

3. MARKS
{
    stu-name:"x" 
    subject :"maths"
    marks: "80"
}

GET /TEACHER/STUDENT/{stu-name}/MARKS/{subject}
GET /TEACHER/STUDENT/
GET /TEACHER/STUDENT/MARKS/

POST /TEACHER/
POST /TEACHER/STUDENT/
POST /TEACHER/STUDENT/MARKS/

PUT /TEACHER/
PUT /TEACHER/STUDENT/{stu-name}
PUT /TEACHER/MARKS/{marks}

PATCH /TEACHER/{teacher-name}
PATCH /TEACHER/STUDENT/{stu-name}
PATCH /TEACHER/{teacher-name}/STUDENT/{stu-name}/MARKS/{marks}

DELETE /TEACHER/{teacher-name}
DELETE /TEACHER/STUDENT/{stu-name}
DELETE /TEACHER/STUDENT/MARKS/{marks}

