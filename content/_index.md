+++
title = "Workshop"
+++




Sorry, this page is currently under construction.


{{ new_block() }}



# Keynote Speaker

{{ grid(
    text = [
        ["Speaker A","Institution A"]
    ],
    urls = [
        "https://tbd"
    ],
    images = [
        "placeholder.svg"
    ],
    narrow = true) }}



{{ new_block() }}



# List of Organizers

{{ grid(
    text = [
        "Organizer A",
        "Organizer B",
        "Organizer C",
        "Organizer D",
        "Organizer E"
    ],
    image_dir = "organizers") }}


{{ new_block() }}



# Schedule

| Time             | Event            |
| ---------------- | ---------------- |
| 12:00pm - 1:00pm | Introduction and Opening Remarks: Speaker Name A     |
| 1:00pm - 2:00pm  | Speaker A        |
| 2:00pm - 3:00pm  | Speaker B        |
| 3:00pm - 4:00pm  | Discussion Panel |



{{ new_block() }}



# Accepted Papers

{{ table(
    data = "papers.csv", 
    columns = ["Title","Authors"],
    button_names = ["paper","poster"], 
    button_data_columns = [3,4], 
    button_output_columns = [1,1]) }}



{{ new_block() }}

