---
layout: default
title: Actualités
---

        <div class="row">
        <!-- /.row -->
		{% for post in site.posts limit:3 %}

 		<div class="col-md-4 img-portfolio">
                    <img class="img-responsive img-hover" src="https://pixabay.com/static/uploads/photo/2012/03/03/22/57/bag-21467_960_720.jpg" alt="noel">
                </a>
                <h3>
                    <a href="{{ post.url }}">{{ post.title }}></a>
                </h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam viverra euismod odio, gravida pellentesque urna varius vitae.</p>
		</div>

		{% endfor %}
		</div>

