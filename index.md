---
layout: default
title: Actualités
---

<div class="row">
        <!-- /.row -->
		{% for post in site.posts limit:3 %}

 		<div class="col-md-4 img-portfolio">
                    <img class="img-responsive img-hover" src="http://placehold.it/700x400" alt="noel">
                </a>
                <h3>
                    <a href="{{ post.url }}">{{ post.title }}></a>
                </h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam viverra euismod odio, gravida pellentesque urna varius vitae.</p>
		</div>

		{% endfor %}
		</div>

