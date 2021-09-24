---
title: Accordion
permalink: /components/accordion
---
### Sample accordion

Below is a sample snippet of accordion

```
<ul class="jekyllcodex_accordion">
  <li>
    <input type="checkbox" id="accordion1">
    <label for="accordion1">Simple</label>
    <div>
      <p>This is a simple one line item</p>
    </div>
  </li>  
  <li>
    <input type="checkbox" id="accordion2">
    <label for="accordion2">Multi-line Block</label>
    <div>
      <p>This is line 1</p>
      <p>This is line 2<br>
        This is line 3</p>
    </div>
  </li>
  <li>
    <input type="checkbox" id="accordion3">
    <label for="accordion3">Multi-line Folded</label>
    <div>
      <p>
        This is all going
        to become just one line\n even though there are multiple lines
      </p>
    </div>
  </li>
  <li>
    <input type="checkbox" id="accordion4">
    <label for="accordion4">Ordered List</label>
    <div>
      <ol>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ol>
    </div>
  </li>
    
  <li>
    <input type="checkbox" id="accordion5">
    <label for="accordion5">Unordered List</label>
    <div>
      <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ul>
    </div>
  </li>
</ul>
```

This will produce
<ul class="jekyllcodex_accordion">
  <li>
    <input type="checkbox" id="accordion6">
    <label for="accordion6">Simple</label>
    <div>
      <p>This is a simple one line item</p>
    </div>
	</li>  
  <li>
    <input type="checkbox" id="accordion2">
    <label for="accordion2">Multi-line Block</label>
    <div>
      <p>This is line 1</p>
      <p>This is line 2<br>
        This is line 3</p>
    </div>
  </li>
  <li>
    <input type="checkbox" id="accordion3">
    <label for="accordion3">Multi-line Folded</label>
    <div>
      <p>
        This is all going
        to become just one line\n even though there are multiple lines
      </p>
    </div>
  </li>
  <li>
    <input type="checkbox" id="accordion4">
    <label for="accordion4">Ordered List</label>
    <div>
      <ol>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ol>
    </div>
  </li>
    
  <li>
    <input type="checkbox" id="accordion5">
    <label for="accordion5">Unordered List</label>
    <div>
      <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ul>
    </div>
  </li>
</ul>

### Important note

If you want to create more than 1 accordion line items in the same page, do take note that 
* the `id` and `for` attribute in the `input` and `label` tags have to be the same. 
* there should not be repeated `id` or `for` attribute in the same page. 

If you have repeated `id` or `for` attributes, the repeated accordion will not open.

#### Where are the `id` and `for` attributes?
You will find the `id` and `for` fields in the `input` and `label` tag.  

In the example below the you will see matching `id="accordion1"` and `for="accordion1"` attributes.
 ```
 <input type="checkbox" id="accordion1">
 <label for="accordion1">Unordered List</label>
```