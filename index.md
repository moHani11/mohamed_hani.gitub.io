# I changed the Hello world ! title

# My Projects
Here is a list of projects that I am working on:
# My Interests
I'm interested in teaching novice coders about computer science!
# My Blog
88 PART 2 Starting Your First Solo Project
I'm really excited to blog my journey on GitHub.com.

<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

# Get in Touch
<ul>
<li><a href="https://instagram.com/{{ site.instagram_username 
}}">instagram</a></li>
<li><a href="https://github.com/{{ site.github_username 
}}">GitHub</a></li>
</ul>
