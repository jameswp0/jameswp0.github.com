---
layout: post
category : lessons
tagline: "Supporting tagline"
tags : [intro, beginner, jekyll, tutorial]
---
{% include JB/setup %}

# What is Jekyll?

Body

## What is Jekyll?

Body

### What is Jekyll?

Body



{% capture text %}...
<body>
  <div id="sidebar"> ... </div>
  <div id="main">
    |.{content}.|
  </div>
</body>
...{% endcapture %}
{% include JB/liquid_raw %}