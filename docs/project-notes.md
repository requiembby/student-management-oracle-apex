# Project Notes: Student Management in Oracle APEX

## Academic evidence

Source: *Oracle APEX Midterm Proofs*, student application `CharosApp_DBA_MidExam`, October 2026.

The coursework evidence shows successful use of the Oracle APEX application and a configured menu hierarchy. This is a high-level functional description, not an executable source export.

## Documented navigation

| Main section | Example pages |
| --- | --- |
| Students | Students Grid, Student Form |
| Reports | Students Chart, Student Report |
| Data Entry | My Page (Student Entry form) |
| Overview | Home |

There are four top-level sections, each with at least one child page.

## Student Entry workflow

The Student Entry form shows five fields: Student ID, First Name, Last Name, Email, and Enrolled Date. A sample record is submitted, and the application displays the message **“Student record added successfully.”** The separate Clear action resets the fields in preparation for the next record.

## Evidence gallery

- `01-navigation-menu.png`: list configuration for top-level and child navigation.
- `02-record-created.png`: confirmation after submitting a test record.
- `03-cleared-student-form.png`: empty entry fields after Clear.
- `04-students-chart.png`: student visualization.
- `05-home-dashboard.png`: overview of application destinations.

## Limitations

The screenshots do not establish production-readiness, authentication rules, or the database's complete SQL schema. The current repository does not include a runnable export, source code, private APEX workspace link, or real student data.
