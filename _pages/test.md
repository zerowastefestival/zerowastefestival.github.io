---
layout: page
permalink: /test/
title: Form input test
---

<form id="myForm" action="https://script.google.com/macros/s/AKfycbwlpfrgCNWGCd2RNcgs99MKM_V7TCM3biToca7cm5WcHGoyuxI/exec">
    First Name:<br>
    <input type="text" name="firstname" style="width:200px" required><br>
    Last Name:<br>
    <input type="text" name="lastname" style="width:200px" required><br>
    Email:<br>
    <input type="text" name="email" style="width:200px" required><br>
	<input type="checkbox" name="workshop" value="workshop_name" required>I want to sign up for the XXX workshop free of charge.<br><br>
    <input type="submit" id="mySubmit" value="Reserve your spot">
</form>

<p>Please press the 'Reserve your spot' button and wait for your reference number to appear below:<br>
<span id="myConf"></span></p>

<FORM>
<INPUT TYPE="button" onClick="history.go(0)" VALUE="Refresh">
</FORM>

<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>

<script type="text/javascript">
$(document).ready(function(){
    // References:
    var $form = $('#myForm');
    var $conf = $('#myConf');
    var $subm = $('#mySubmit');	
    var $impt = $form.find(':input').not(':button, :submit, :reset, :hidden');
    // Submit function:
    $form.submit(function(){
        $.post($(this).attr('action'), $(this).serialize(), function(response){
     // On success, clear all inputs;      $impt.val('').attr('value','').removeAttr('checked').removeAttr('selected');
     // Write a confirmation message:
            $conf.html("You're in! Your reference number is ZW1812WS1 in combination with your full name. Please refresh this page to book another spot.");			
            alert("You're in! Your reference number is ZW1812WS1 in combination with your full name. Please refresh this page to book another spot.");
     // Disable the submit button:
            $subm.prop('disabled', true);
        },'json');
        return false;
    });
});
</script>

