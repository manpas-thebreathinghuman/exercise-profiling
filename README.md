<img width="1421" height="141" alt="Screenshot 2026-07-11 151241" src="https://github.com/user-attachments/assets/d681ad4e-b698-446d-98b8-0aa88bd28ea8" />
<img width="1433" height="107" alt="Screenshot 2026-07-11 151246" src="https://github.com/user-attachments/assets/b115a3db-091d-4ae1-8020-b2e74e4fe316" />

apparently the fix is easy
public List<StudentCourse> getAllStudentsWithCourses() {
    return studentCourseRepository.findAll();
}
it gives 45% improvement to /all-student
25% improvement to /highest-gpa
and -5% to /all-student-name
which is average 21%