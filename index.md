---
layout: page
title: Lesson Plans
---

What are you going to do with your kids?  We decided to make some short lesson plans to help you keep your kids busy for at least a little bit trhoughout the day.

## First Grade

### Math
* **Graphs**

  {%- if site.categories.graphs.size > 0 -%}
    <ul class="list-unstyled">
      {%- for post in  site.categories.math -%}
      <li>
        <span class="text-muted">
          {%- assign date_format = "%b %-d, %Y" -%}
          {{ post.date | date: date_format }}
        </span>
        <p class="h5">
          <a href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </p>
        {%- if site.show_excerpts -%}
          {{ post.excerpt }}
        {%- endif -%}
      </li>
      {%- endfor -%}
    </ul>
  {%- endif -%}


  [Pizza VS CheeseBurgers VS Frenchfries](/Math/Graph-2020-3-18.md) 

### Reading

Here we have two possibilities:

### Writing

Here we have two possibilities:

### Art

* [LUNCH DOODLES with Mo Willems! Episode 1](https://www.youtube.com/watch?v=RmzjCPQv3y8)


{{ site.categories | jsonify  }}

{{ site.categories.math | jsonify  }}