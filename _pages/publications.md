---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<h2>📚 Recent Publications (latest 20)</h2>
{% if site.author.googlescholar %}
  <div class="wordwrap">Here's the list of my latest 20 publications. You can find a complete list on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% include publications  limit = 20  link=True %}

<!-- 

<!-- Adding three linkable buttons to run custom code -->
<!-- <div style="margin-top: 20px;">
  <button onclick="runCustomCode1()" style="padding: 10px 20px; margin-right: 10px;">All publication</button>
  <button onclick="runCustomCode2()" style="padding: 10px 20px; margin-right: 10px;">Latest 10 publication</button>
</div>
 --> 



<!-- 
<script>
  function runCustomCode1() {
    // Your custom code for the first button
        window.location.reload()

    {% include publications link=True %}

  }

  function runCustomCode2() {
    // Your custom code for the second button
    window.location.reload()

    

  } -->


<!-- </script> -->
