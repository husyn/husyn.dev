---
title: "Contact"
permalink: "/contact.html"
---
<div class="col-lg-6 col-md-12">
          <form action="mailto:hussain@husyn.dev?subject=husyn.dev-Contact" id="contactForm" method="POST"
            enctype="text/plain" target="_blank">
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <input type="text" class="form-control" id="name" name="Name" placeholder="Name"
                    pattern="pattern=[A-Z\a-z]{3,20}" required data-error="Please enter your name">
                  <div class="help-block with-errors"></div>
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-group">
                  <input type="text" class="form-control" id="email" name="Email" placeholder="Email" required
                    data-error="Please enter your Email">
                  <div class="help-block with-errors"></div>
                </div>
              </div>
              <div class="col-md-12">
                <div class="form-group">
                  <textarea class="form-control" id="message" name="Message" placeholder="Write Message" rows="4"
                    data-error="Write your message" required></textarea>
                  <div class="help-block with-errors"></div>
                </div>
                <div class="submit-button">
                  <button class="btn btn-common" id="submit" type="submit">Submit</button>
                  <div id="msgSubmit" class="h3 hidden"></div>
                  <div class="clearfix"></div>
                </div>
              </div>
            </div>
          </form>
        </div>
