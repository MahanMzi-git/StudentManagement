# StudentManagement
a program for writing student info and modify it with RandomAccess class
question :
Consider the students file format given in the last example.
﻿﻿Write a complete Java program which will implement a Student class.
﻿﻿In the student class you will have the following functionalities.
Pay attention that the structure of the students.txt file should never be broken.
One class constructor that accepts the full filepath for the students file as its only argument.
﻿﻿﻿A method called modify(stdid, field, new_value) which will modify the requested field to the provided new value of the given student. You should consider finding the student only by reading the student ids and stopping once you find.
﻿﻿﻿An insert(stdid,name, cgpa, date, gender) method which will append a student to the end of the student file.
﻿﻿﻿A delete(stdid) method which will delete a student record (line) completely.
﻿﻿﻿display() which will display all students on the monitor (tab separated).
﻿﻿﻿A method called stats) which will create a new file called stats.txt in the same path of the students. txt which will contain how many female and male students there are, the average gpa and the total student count on separate files.
How the student class will be used is your experiment which will be explained and tested during the lab hours.
