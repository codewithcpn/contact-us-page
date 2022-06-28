 <!--=======Contact-Section Starts Here=======-->
   <div class="container">
     <form  method="POST">
       <div class="row py-3">
           <div class="col-md-6">
               
               <div class="col-md-12 my-1">
                  <label for="inlineFormInputGroupUsername">Your Name*</label>
                  <div class="input-group">
                    <div class="input-group-prepend">
                      <div class="input-group-text"><i class="fa fa-user" aria-hidden="true"></i></div>
                    </div>
                    <input type="text" class="form-control" id="inlineFormInputGroupUsername" name="name" placeholder="Name" required>
                  </div>
                </div><br>
                <div class="col-md-12 my-1">
                  <label for="inlineFormInputGroupUsername">Your Phone*</label>
                  <div class="input-group">
                    <div class="input-group-prepend">
                      <div class="input-group-text"><i class="fa fa-mobile" aria-hidden="true"></i></div>
                    </div>
                    <input type="text" class="form-control" id="inlineFormInputGroupUsername" name="phone" placeholder="Phone" required>
                  </div>
                </div><br>
                 <div class="col-md-12 my-1">
                  <label for="inlineFormInputGroupUsername">Your Email*</label>
                  <div class="input-group">
                    <div class="input-group-prepend">
                      <div class="input-group-text"><i class="fa fa-envelope" aria-hidden="true"></i></div>
                    </div>
                    <input type="text" class="form-control" id="inlineFormInputGroupUsername" name="email" placeholder="Email" required>
                  </div>
                </div></br>
                 <div class="col-md-12 my-1">
                  <label for="exampleFormControlSelect2">Your Subject*</label>
                  <div class="input-group">
                    <div class="input-group-prepend">
                      <div class="input-group-text"><i class="fa fa-sort" aria-hidden="true"></i></div>
                    </div>
                    <select class="form-control" name="sub" required>
                      <option value="Generall Enquiry">Generall Enquiry</option>
                      <option value="Mutual Funds Enquiry">Mutual Funds Enquiry</option>
                      <option value="Equity Deposit Funds Enquiry">Equity Deposit Funds Enquiry</option>
                      <option value="Insurance Plan Enquiry">Insurance Plan Enquiry</option>
                      <option value="Text Saving Plan Enquiry">Text Saving Plan Enquiry</option>
                    </select>
                  </div>
                </div></br>
                 <div class="col-md-12 my-1">
                  <label for="inlineFormInputGroupUsername">Your Message*</label>
                  <div class="input-group">
                     <textarea class="form-control" name="msg" id="exampleFormControlTextarea1" rows="3" required></textarea>
                  </div>
                </div><br>
                <div class="col-md-12 my-1">
                 <button type="submit" name="submit" value="submit" class="btn btn-lg btn-primary">Submit</button>
                </div>
                
           </div>
           <div class="col-md-6">
               <div class="contact--thumb">
                        <img src="<?php echo base_url('');?>assetss/images/contact/contact01.png" alt="contact">
               </div>
           </div>
       </div>
     </form>
   </div>

    <!--=======Contact-Section Ends Here=======-->
