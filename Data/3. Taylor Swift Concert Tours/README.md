### Data Source ###

Data obtained from: https://www.kaggle.com/datasets/gayu14/taylor-concert-tours-impact-on-attendance-and

### Data Transformation ###

1. Promote First Row to Headers
2. Split column Attendance "(tickets sold / available)" into "Tickets Sold" and "Tickets Available".
3. Remove NULLs in "Revenue" and "Tickets Available" columns. Around 40 rows.
4. Create "Tickets Unsold" column.
5. Assign the correct data types and clean up "Revenue" column removing the text "$" character.
