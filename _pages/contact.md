---
layout: page
title: Contactaține
permalink: /contact
comments: false
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Va rugăm în forma de mai jos să ne scrieți. {{site.name}}, vom lua legătura în cel mai scurt timp!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Numele*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="Adresa E-mail*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Mesajul*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Trimite">
</form>