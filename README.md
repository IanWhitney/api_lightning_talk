# API Endpoints

## [Liberal Education Courses](http://umn-asr.github.io/liberal_education_courses/)

- Documentation at: https://liberal-education-courses.umn.edu/
- UMNTC Only
- JSON Only

### Examples

- https://liberal-education-courses.umn.edu/courses.json?q=writing_intensive=false
- https://liberal-education-courses.umn.edu/courses.json?q=writing_intensive=false,designated_theme=dsj
- https://liberal-education-courses.umn.edu/courses.json?q=writing_intensive=false,designated_theme=dsj,subject=aas
- https://liberal-education-courses.umn.edu/courses.json?q=writing_intensive=false,designated_theme=dsj,subject=aas|afro

### Used By

- http://onestop.umn.edu/degree_planning/lib_eds/fall_2010_requirements/arts_humanities.html
- http://libedme.herokuapp.com/#/

## [Sessions Data Service](http://umn-asr.github.io/sessions_data_service/)

- Documentation at: http://sessions.umn.edu/
- All Campuses, undergrad and grad
- JSON and XML

### Examples

- http://sessions.umn.edu/sessions.json?q=academic_career_id=DENT|MED
- http://sessions.umn.edu/sessions.json?q=academic_career_id=DENT|MED,term_id=1155
- http://sessions.umn.edu/sessions.json?q=academic_career_id=DENT|MED,term_id=1155,institution_id=umndl

### Used By

- http://www.classroom.umn.edu/scheduling/academic_scheduling/sessions.html

## [Courses Data Service](http://umn-asr.github.io/courses/)

- Documentation at: http://courses.umn.edu/
- All Campuses
- Multiple Terms
- JSON and XML

### Examples

- http://courses.umn.edu/campuses/umntc/terms/1163/courses.json?q=subject_id=AFRO,catalog_number=3433
- http://courses.umn.edu/campuses/umntc/terms/1163/courses.json?q=subject_id=AFRO
- http://courses.umn.edu/campuses/umntc/terms/1163/courses.json?q=subject_id=AFRO|AAS
- http://courses.umn.edu/campuses/umntc/terms/1163/courses.json?q=subject_id=AFRO|AAS,catalog_number>4000
- [http://courses.umn.edu/campuses/umntc/terms/1163/courses.json?q=subject_id=AFRO|AAS,catalog_number>4000,catalog_number<5000](http://courses.umn.edu/campuses/umntc/terms/1163/courses.json?q=subject_id=AFRO|AAS,catalog_number>4000,catalog_number<5000)

- http://courses.umn.edu/campuses/umndl/terms/1163/courses.json?q=instruction_mode_id=ID

- http://courses.umn.edu/campuses/umntc/terms/1155/courses.json?q=locations=STPAUL
- http://courses.umn.edu/campuses/umntc/terms/1163/courses.json?q=course_attribute_id=WI
- http://courses.umn.edu/campuses/umntc/terms/1163/courses.json?q=course_attribute_id=WI,course_attribute_id=dsj
- http://courses.umn.edu/campuses/umntc/terms/1163/courses.json?q=course_attribute_id=WI,course_attribute_id=dsj,subject_id=aas|afro

- http://courses.umn.edu/campuses/umnmo/terms/1163/courses.json?q=course_attribute_family=GER

### Used By

- Maybe You?
