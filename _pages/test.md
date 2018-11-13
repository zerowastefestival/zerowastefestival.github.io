---
layout: page
permalink: /test/
title: Form input test
---



<script src="https://wzrd.in/standalone/formdata-polyfill"></script>
<script src="https://wzrd.in/standalone/promise-polyfill@latest"></script>
<script src="https://wzrd.in/standalone/whatwg-fetch@latest"></script>

<script>
  const scriptURL = 'https://script.google.com/macros/s/AKfycbwrTTPvPGwBsk4K2nXX0EdP8ryai_FAKf03AxlFkal410pcTJw-/exec'
  const form = document.forms['submit-to-google-sheet']

  form.addEventListener('submit', e => {
    e.preventDefault()
    fetch(scriptURL, { method: 'POST', body: new FormData(form)})
      .then(response => console.log('Success!', response))
      .catch(error => console.error('Error!', error.message))
  })
</script>

dssdkl


<form id="test-form">
  
  <div>
    <label>Name</label>
    <input type="text" name="name" style="width: 200px;" required><br>
  </div>

  <div>
    <label>Field 2</label>
    <input type="checkbox" name="workshop" value="yes" required> workshop XYZ<br>
  </div>
  
  <div>
    <button type="submit">Book your spot</button>
  </div>

</form>