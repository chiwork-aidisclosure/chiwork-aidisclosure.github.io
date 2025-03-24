+++
title = "Program"
page_template = "item.html"
sort_by = "date"
[extra]
+++



## Schedule

| Time             | Event            |
| ---------------- | ---------------- |
| 9:00am - 9:10am | Introduction     |
| 9:10am - 10:10am  | Keynote        |
| 10:10am - 11:10am  | Participant Presentations       |
| 11:10am - 11:40am  | Social Coffee Break with Interactive Posters |
| 11:40am - 12:50pm  | Group Activity |
| 12:50pm - 1:00pm  | Closing Remarks |


{{ new_block() }}






## Participant Presentations

{{ table(
    data = "papers.csv", 
    columns = ["Title","Authors"],
    button_names = ["paper","poster"], 
    button_data_columns = [3,4], 
    button_output_columns = [1,1]) }}



{{ new_block() }}