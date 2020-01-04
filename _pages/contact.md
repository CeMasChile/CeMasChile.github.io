---
layout: page
title: Contacto
permalink: /contact
---
<div class="bg-white container">
  <div class="row" style="padding: 100px;">
    <div class="col-md-6">
      <form action="https://usebasin.com/f/d5471c201e0d" method="POST" id="contact-form">
        <div class="control-group">
          <div class="form-group floating-label-form-group controls mb-0 pb-2">
            <label class="lead text-muted mb-0">Nombre organizacion</label>
            <input class="form-control" name="organization" type="text" placeholder="Organización" required="required" data-validation-required-message="Por favor, ingrese una organización. Si usted es una persona particular, tipee 'Particular'.">
            <p class="help-block text-danger"></p>
          </div>
        </div>
        <div class="control-group">
          <div class="form-group floating-label-form-group controls mb-0 pb-2">
            <label class="lead text-muted mb-0">Nombre Persona</label>
            <input class="form-control" name="name" type="text" placeholder="Nombre " required="required" data-validation-required-message="Por favor, ingrese su nombre">
            <p class="help-block text-danger"></p>
          </div>
        </div>
        <div class="control-group">
          <div class="form-group floating-label-form-group controls mb-0 pb-2">
            <label class="lead text-muted mb-0">Correo de contacto</label>
            <input class="form-control" name="email" type="email" placeholder="example@example.com" required="required" data-validation-required-message="Por favor, ingrese su email.  ">
            <p class="help-block text-danger"></p>
          </div>
        </div>
        <div class="control-group">
          <div class="form-group floating-label-form-group controls mb-0 pb-2">
            <label class="lead text-muted mb-0">Area</label>
            <input class="form-control" name="work-area" type="text" placeholder="Area de trabajo" required="required" data-validation-required-message="Por favor, ingrese su Area de Trabajo">
            <p class="help-block text-danger"></p>
          </div>
        </div>
        <div class="control-group">
          <div class="form-group floating-label-form-group controls mb-0 pb-2">
            <label class="lead text-muted mb-0">Descripción</label>
            <textarea class="form-control" name="message" rows="5" placeholder="Mensaje" required="required" data-validation-required-message="Por favor, ingrese un mensaje."></textarea>
            <p class="help-block text-danger"></p>
          </div>
        </div>
        <br>
        <div class="form-group">
          <button type="submit" class="primary-button">Enviar</button>
        </div>
      </form>
    </div>
    <div class="col-md-6 text-center py-5">
      <img src="../assets/images/about-1.png" alt="" class="img-fluid mb-4 mb-lg-0">
    </div>
  </div>
</div>

<script type="text/javascript">
$.ajax({
  url: "//https://usebasin.com/f/d5471c201e0d", 
  method: "POST",
  data: {message: "hello!"},
  dataType: "json"
});


</script>