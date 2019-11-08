---
layout: page
title: Contacto
permalink: /contact
---
<div class="bg-white py-5">
    <div class="container py-5">
        <!-- Contact Section Heading -->
      <h2 class="title">Contacto</h2> 
      <!-- Contact Section Form -->
      <div class="row">
        <div class="col-lg-8 mx-auto">
          <!-- To configure the contact form email address, go to mail/contact_me.php and update the email address in the PHP file on line 19. -->
          <form name="sentMessage" id="contactForm" novalidate="novalidate">
            <div class="control-group">
              <div class="form-group floating-label-form-group controls mb-0 pb-2">
                <label>Nombre organizacion</label>
                <input class="form-control" id="name" type="text" placeholder="Organización" required="required" data-validation-required-message="Por favor, ingrese una organización. Si es una persona particula, tipee 'Particular'.">
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="control-group">
              <div class="form-group floating-label-form-group controls mb-0 pb-2">
                <label>Nombre Persona</label>
                <input class="form-control" id="name" type="text" placeholder="Nombre " required="required" data-validation-required-message="Por favor, ingrese su nombre">
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="control-group">
              <div class="form-group floating-label-form-group controls mb-0 pb-2">
                <label>Correo de contacto</label>
                <input class="form-control" id="email" type="email" placeholder="example@example.com" required="required" data-validation-required-message="Por favor, ingrese su email.  ">
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="control-group">
              <div class="form-group floating-label-form-group controls mb-0 pb-2">
                <label>Area</label>
                <input class="form-control" id="name" type="text" placeholder="Area de trabajo" required="required" data-validation-required-message="Por favor, ingrese su Area de Trabajo">
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="control-group">
              <div class="form-group floating-label-form-group controls mb-0 pb-2">
                <label>Descripción</label>
                <textarea class="form-control" id="message" rows="5" placeholder="Mensaje" required="required" data-validation-required-message="Por favor, ingrese un mensaje."></textarea>
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <br>
            <div id="success"></div>
            <div class="form-group">
              <button type="submit" class="btn btn-primary btn-xl" id="sendMessageButton">Send</button>
            </div>
          </form>
        </div>
      </div>
    </div>
</div>