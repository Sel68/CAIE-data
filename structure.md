subjects.csv
subject_code,name

papers.csv
subject_code,year,session,paper_number,variant,duration,total_marks

questions.csv
subject_code,year,session,paper_number,variant,question_number,label,marks,text_statement,image_path
(Note: label is NULL for general question context/statements)

markpoints.csv
subject_code,year,session,paper_number,variant,question_number,label,point_number,description,marks,type

examiner_comments.csv
subject_code,year,session,paper_number,variant,question_number,label,comment_text

grade_boundaries.csv
subject_code,year,session,paper_number,variant,grade,min_mark

topics.csv
subject_code, topic_name

question_topics.csv
subject_code,year,session,paper_number,variant,question_number,topic_name