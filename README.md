# Jaspreet-Singh-Brar
1) title 
let b= document.querySelector('.item-page__main-title');
undefined
b
<h1 title=​"the sun and her flowers" data-a8n=​"item-page__main-title" class=​"item-page__main-title" style=​"word-wrap:​ break-word;​">​the sun and her flowers​</h1>​
bv-primary.js:74 scout-to-render: 5166ms
b.textContent="life is hard and so my lessons ";
"life is hard and so my lessons "

2)picture
let image= document.querySelector(".product-image__image--single");
undefined
image
<img class=​"product-image__image--single" src=​"https:​/​/​dynamic.indigoimages.ca/​books/​1501175262.jpg?altimages=false&scaleup=true&maxheight=515&width=380&quality=85&sale=40&lang=en" data-a8n=​"product-image__image" alt=​"the sun and her flowers by Rupi Kaur">​
image.src
"https://dynamic.indigoimages.ca/books/1501175262.jpg?altimages=false&scaleup=true&maxheight=515&width=380&quality=85&sale=40&lang=en"
image.src="https://upload.wikimedia.org/wikipedia/en/e/e4/A_Hard_Day_2014.jpg";
9781501175268-item.html?ref=by-shop%3abooks%3abooks-the-fall-list%3afall-list-2017%3a1%3a:1 [Report Only] Refused to load the image 'https://upload.wikimedia.org/wikipedia/en/e/e4/A_Hard_Day_2014.jpg' because it violates the following Content Security Policy directive: "img-src 'self' data: blob: *.indigo.ca *.indigoimages.ca *.bazaarvoice.com *.nr-data.net https://*.cloudfront.net https://*.doubleclick.net https://*.facebook.com https://*.googleapis.com https://*.google-analytics.com https://*.google.com https://*.google.ca https://*.gstatic.com https://*.pinimg.com https://*.twimg.com https://*.twitter.com https://*.webtype.com *.omtrdc.net https://t.co https://notify.bugsnag.com https://s3.amazonaws.com https://*.checkout.visa.com https://tracker.marinsm.com https://kbimages1-a.akamaihd.net www.paypalobjects.com https://*.paypal.com https://*.piwikpro.com https://secure.adnxs.com https://www.offlinx.com https://gtrk.s3.amazonaws.com https://heapanalytics.com".

"https://upload.wikimedia.org/wikipedia/en/e/e4/A_Hard_Day_2014.jpg"

3) Navigation
let jass = ["I" , "am" , "jaspreet" , "singh" , "brar" , "and" , "idont" , "know" , "french" , "hola"];    
undefined
let jas = document.querySelectorAll('[class^=top-nav__list-link--active]');
undefined
jas
[a.top-nav__list-link--active]
jas = Array.from(document.querySelectorAll(''[class^=top-nav__list-link--active]'));jas = Array.from(document.querySelectorAll('[class^=top-nav__list-link--active]'));
[a.top-nav__list-link--active]jass.map( (navitem, idx) => navitem.textContent = jass[idx]);
(10) ["I", "am", "jaspreet", "singh", "brar", "and", "idont", "know", "french", "hola"]
