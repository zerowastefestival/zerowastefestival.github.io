---
layout: post
title: Learn to Knit with Revived Yarn at the Christmas Festival

category: 2018-12-festival

image:
  #feature: 
  teaser : events/2018-12-festival/teaser-revived-yarn-knitting.jpg

sidebar: true
share: true
---

Revived Yarn will host a beginner's knitting workshop at the upcoming Zero Waste Christmas Festival. Sign up for free if you would like to learn how to make simple and fashionable items for the homeless.

## Kickstarter for new knitters to volunteer with Revived Yarn

![Revived Yarn]({{ site.baseurl }}/images/logos-external/logo-revived-yarn.png "Revived Yarn"){:style="float: top;margin-right: 10px;height: 150px;"}

[Revived Yarn](https://www.facebook.com/revivedyarn) are a group of volunteers who collect donations of unused yarn and upcycle it to create handmade garments of high quality distributed to the homeless community in Dublin. If you would like to give back and help them to warm the homeless but you don't know how to knit or you are a beginner, this workshop is for you! In this class you will receive a kit containing the yarn to be upcycled and a pattern. You will learn the basic stitches of knitting and all the steps to make a simple and fashionable item for the homeless. You can sign up free of charge [below](#sign-up). If you wish, you can make a small donation after the workshop to support their initiative!

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/revivedyarn?ref_src=twsrc%5Etfw">@revivedyarn</a> will host a beginner’s <a href="https://twitter.com/hashtag/knitting?src=hash&amp;ref_src=twsrc%5Etfw">#knitting</a> workshop to benefit the homeless of <a href="https://twitter.com/hashtag/Dublin?src=hash&amp;ref_src=twsrc%5Etfw">#Dublin</a> at the upcoming Zero Waste Christmas Festival, hosted at <a href="https://twitter.com/GreenDoorMarket?ref_src=twsrc%5Etfw">@GreenDoorMarket</a>. Sign up for free here: <a href="https://t.co/XVJGpou3BL">https://t.co/XVJGpou3BL</a> <a href="https://twitter.com/hashtag/zerowaste?src=hash&amp;ref_src=twsrc%5Etfw">#zerowaste</a> <a href="https://twitter.com/hashtag/zerowastefest?src=hash&amp;ref_src=twsrc%5Etfw">#zerowastefest</a> <a href="https://twitter.com/hashtag/freeevent?src=hash&amp;ref_src=twsrc%5Etfw">#freeevent</a> <a href="https://twitter.com/hashtag/DublinEvents?src=hash&amp;ref_src=twsrc%5Etfw">#DublinEvents</a> <a href="https://twitter.com/hashtag/Recycle?src=hash&amp;ref_src=twsrc%5Etfw">#Recycle</a> <a href="https://t.co/D2pJDFEp3W">pic.twitter.com/D2pJDFEp3W</a></p>&mdash; Zero Waste Festival (@ZeroWasteFest) <a href="https://twitter.com/ZeroWasteFest/status/1063159705638363136?ref_src=twsrc%5Etfw">November 15, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

The workshop will take place during the [Zero Waste Christmas Festival](/2018-12-festival) on December 2, 2018, at the Green Door Market from 12:30 to 2:30 pm.

## Sign up

We want to have enough recycled yarn and starter kits ready for you to start your knitting career! So if you're interested, we kindly ask you to sign up for this free (donations welcome) workshop by using the form below. We will use your name and email address to contact you closer to the Festival with more information.

<form id="myForm" action="https://script.google.com/macros/s/AKfycbwlpfrgCNWGCd2RNcgs99MKM_V7TCM3biToca7cm5WcHGoyuxI/exec">
    First Name:<br>
    <input type="text" name="firstname" style="width:200px" required><br>
    Last Name:<br>
    <input type="text" name="lastname" style="width:200px" required><br>
    Email:<br>
    <input type="email" name="email" style="width:200px" required><br>
	<input type="checkbox" name="workshop" value="knitting_revived_yarn" required>I want to sign up for the "Kickstarter for new knitters to volunteer with Revived Yarn" workshop free of charge.<br><br>
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








