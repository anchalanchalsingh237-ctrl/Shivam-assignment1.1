Here is the GitHub README answer for *Assignment 4.3* - without code, only explanation:

---

### Assignment 4.3 — Student Marks Table

*Objective:*
To create a student marksheet table using HTML that displays marks of students.

*What I Built:*
I created a table named `Student Marksheet - 2024` using `<caption>` as the title.

The table contains *5 students* (Aman, Riya, Karan, Simran, Rahul) and *3 subjects* (Maths, Science, English).

*Structure Used:*

1.  *`<table>`, `<tr>`, `<th>`, `<td>`:* I used `<table>` for the whole table, `<tr>` for each row, `<th>` for header cells and `<td>` for data cells.

2.  *`<thead>, <tbody>, <tfoot>`:*
    - `<thead>` contains the headers - Roll No, Name, Subjects, Total.
    - `<tbody>` contains the actual data of 5 students.
    - `<tfoot>` contains the footer which shows the Average Marks.

3.  *`<caption>`:* Used to give title to the table at the top.

4.  *Footer Total/Average:* In the footer, I calculated and displayed the average of total marks of all students.

5.  *Colspan and Rowspan:*
    - `rowspan="2"` is used for Roll No, Name and Total so they cover 2 header rows.
    - `colspan="3"` is used for Subjects heading to merge 3 subjects columns into one main heading.
    - `colspan="5"` is used in the footer to merge cells for "Average Marks" label.

6.  *Meaningful Headers:* All headers are meaningful like Roll No, Student Name, Maths, Science, English, Total.

*Submission Files:*
1.  `marksheet.html`
2.  Screenshot of the table in browser