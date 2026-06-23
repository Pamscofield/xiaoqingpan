---
title: Habit tracking via Pixela
summary: Track daily habits via Pixela
date: 2025-11-27

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Pixela**]()'

authors:
  - admin

tags:
  - python
  - Pixela
---

*Back to daily python learning... with some fun tasks*

- **100 Days of Code** python course is from Udemy by Angela Yu
- Day 37
- [Pixela](https://pixe.la/)

```python
#!/usr/bin/env python3
import requests
from datetime import datetime

# ToDo1: Create a user
pixela_endpoint = "https://pixe.la/v1/users"
USERNAME = "artemis"
TOKEN = "lkaowngn1343na;<jgkrn"

user_params = {
    "token": TOKEN,
    "username": USERNAME,
    "agreeTermsOfService": "yes",
    "notMinor": "yes",
}

# ToDo2: create a graph 
graph_endpoint = f"{pixela_endpoint}/{USERNAME}/graphs"

graph_config = {
    "id": "graph1",
    "name": "German",
    "unit": "hours",
    "type": "float",
    "color": "sora",
}

headers = {
    "X-USER-TOKEN": TOKEN
}

# response = requests.post(url=graph_endpoint, json=graph_config, headers=headers)
# print(response.text)

# ToDo3: post a graph
post_endpoint = f"{graph_endpoint}/{graph_config['id']}"

today= datetime.now()

post_config = {
    "date": today.strftime("%Y%m%d"),
    "quantity": "1",
}

# response = requests.post(url=post_endpoint, json=post_config, headers=headers)
# print(response.text)

# ToDo4: update the graph
update_endpoint = f"{post_endpoint}/{today.strftime('%Y%m%d')}"

update_config = {
    "quantity": "0.3",
}

response = requests.post(url=update_endpoint, json=update_config, headers=headers)
print(response.text)
```

Note that the GUI I use (cursor) interpreter is complicated, so it's better to "tell it" which python to use. Hope I can really learn German Jaden Tag (not possible!)