---
layout: page
permalink: /shop/
title: "Shop"
---

Buy tickets here: 

<!-- link example -->
<a href="https://zwf.foxycart.com/cart?name=Cool%20Example&price=10&color=red&code=sku123">Add a red Cool Example</a>
<!-- form example -->
<form action="https://zwf.foxycart.com/cart" method="post" accept-charset="utf-8">
<input type="hidden" name="name" value="Cool Example" />
<input type="hidden" name="price" value="10" />
<input type="hidden" name="code" value="sku123" />
<label class="label_left">Size</label>
<select name="size">
    <option value="small">Small</option>
    <option value="medium">Medium</option>
    <option value="large">Large</option>
</select>
<input type="submit" value="Add a Cool Example" class="submit" />
</form>

