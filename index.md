---
title: "Welcome to My Blog"
date: 2025-06-10
---

# 🚀  
This is where I share articles about Python and programming.

## 📌 List of Articles  

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** ({{ post.date | date: "%d-%m-%Y" }})  
{% endfor %}
permalink: /:year/:month/:day/:title/

📌 The blog is updated regularly—stay tuned for new posts!
