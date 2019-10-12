Please create a local database for a student examination system(student_examination_sys) with three tables:

1. Table of student:

   |  id  | name | age  | sex  |
   | :--: | :--: | :--: | :--: |
   | 001  | zhangsan |  18  |  male  |
   | 002  | lisi |  20  |  female  |

2. Table of subject:

   |  id  | subject | teacher |   description    |
   | :--: | :-----: | :-----: | :--------------: |
   | 1001 |  Chinese   | Mr. Wang  | the exam is easy |
   | 1002 |  math   | Miss Liu  |  the exam is difficult |

3. Table of score:

   |  id  | student_id | subject_id | score |
   | :--: | :--------: | :--------: | :---: |
   |  1   |    001     |    1001    |  80   |
   |  2   |    002     |    1002    |  60   |
   |  3   |    001     |    1001    |  70   |
   |  4   |    002     |    1002    | 60.5  |

Please use SQL to implement above demands and provide a description with a screenshot of the implementation result.
