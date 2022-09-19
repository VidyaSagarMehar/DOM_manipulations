# DOM Manipulation Assignmnt Answer

### 1.  Website - [dev to](https://dev.to/)

Code - 
```console
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerText = "Vidya Sagar Mehar"

document.querySelector(".side-bar .crayons-card p").innerHTML = "I write code"

```
Output - 

Changes "DEV Community 👩‍💻👨‍💻 is a community of 925,602 amazing developers" to Name-  "Vidya Sagar Mehar" passion = " I write code".

![](./assignment01/de.toOutput.png)

### 2. Website Name: [Apple](https://support.apple.com/en-in)

Code -
```console
let empArr = [];

document.querySelectorAll(".as-imagegrid-item").forEach((ex) => 
    empArr.push(ex.innerText.replace("\nSupport", "")));

console.log(empArr)
```

Output -

Extracted the product name and stored them in array.
> (7) ['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']


### 3. Website - [Youtube](https://support.google.com/youtube/#topic=9257498)

Code -
```console
const sec = document.createElement("section")

sec.innerHTML = "My New FAQ"

document.querySelector(".accordion-homepage").appendChild(sec)

```

Output -

Added a new FAQ 

![](./assignment01/youtubeOutput.png)



### 4. Website [Oneplus](https://www.oneplus.in/support)

Code -
```console
document.querySelector(".customer-support .service-number").innerText = "+91 77177 67744"
```

Output -

Changed phone no. to my Mobile no.

![](./assignment01/4oneplus.png)

### 5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/) 

Code -
```console
let newid = document.querySelector(".feature-column-carousel__button .cta")

newid.setAttribute("id", "checkO")
// It sets attribute, if there is no atribute it creates one.

document.getElementById("checkO").innerText = "Check Out"
```

Output -
Changes button from "Buy now" to "Check Out" 

![](./assignment01/05samsung.png)


###  6. Webiste Name: [Adidas](https://www.adidas.co.in/)

Code -
```console
function searchBG(){
    document.querySelector(".searchinput___zXLAR").style.backgroundColor="red";
}

document.addEventListener('mouseover',change_bg);
```

Output -

Background colour changed with "Red".

![](./assignment01/06search.png)

###  7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

Code -
```console
function search(text) {
	let input = document.querySelector("#top-nav-search-input");
	input.value = text;
	let btn = document.querySelector(".search-form");
	btn.submit();
}
search("Css Selector");

```

Output -

Doing search operation with dom manupulation.

![](./assignment01/07MDN.png)

###  8. Webiste Name: [Google](https://www.google.com/)

Code -
```console
let arr = document.querySelectorAll("#SIvCob a");

[...arr].forEach((element) => {
    var array = ["தமிழ்", "ગુજરાતી", "ಕನ್ನಡ", "മലയാളം", "ਪੰਜਾਬੀ"];
    if(array.includes(element.innerText)){
        element.remove();
    }
});
```

Output -

Some languages are removed.


![](assignment01/08google.png)

###   9. Webiste Name: [Code Wars](https://www.codewars.com/)

Code -
```console
document.querySelector(".content-width-extra-large .display-heading-1").style.fontFamily = "serif"

document.querySelector(".content-width-extra-large .display-heading-1").style.color = "#8B2E1D";
```

Output -

![](./assignment01/09codewars.png)

### 10.  Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

Code -
```console
function changeBG(){
    document.querySelector(".btn-cta-big .login-btn-text").style.backgroundColor = "red";
};

document.addEventListener("click", changeBG)
```

Output -

![](./assignment01/10codeCamp.png)

###   11. Webiste Name: [realme](https://www.realme.com/in/)

Code -
```console
document.querySelector(".wrapper .gtag .icon-logo ").style.backgroundImage = "url(https://ineuron.ai/images/ineuron-logo.png)";
```

Output -

![](./assignment01/11realme.png)


###   12. Webiste Name: [Github](https://github.com/)

Code -
```console
document.querySelector(".js-repos-container h2 a").style.backgroundColor = "blue";
```

Output -

![](./assignment01/12github.png)


###   13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

Code -
```console
document.querySelector(".fl-module ").innerHTML = "JSBOOTCAMP"
'JSBOOTCAMP'
```

Output -

![](./assignment01/13hackerrank.png)


### 14. Webiste Name: [Asus](https://www.asus.com/in/)

Code -
```console
document.querySelector(".HotDealsAll__Heading__2fIbe").style.fontSize = "100px";
'100px'
```

Output - 

![](./assignment01/14Asus.png)

### 15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

```console
document.querySelector(".ps-title a").style.textAlign = "right";
```
Output-

![](./assignment01/15dell.png)

### 16. Webiste Name: [Vercel](https://vercel.com/)

```console
document.querySelector(".section-title_title__VEDfK").innerHTML = "Start with Scratch"
```
Output-

![](./assignment01/16versel.png)

### 17.Webiste Name: [Sony](https://www.sony.co.in/)

```console
document.querySelector(".btn-container a").innerHTML = new Date();
```
Output-
![](./assignment01/17sony.png)

### 18. Webiste Name: [Philips](https://www.philips.co.in/)

```console
document.querySelector(".p-footer").style.backgroundColor = "orange";
```
Output-
![](./assignment01/18philips.png)


### 19. Webiste Name: [Canon](https://in.canon/)

```console
document.querySelector(".logo").getAttribute("src")
```
Output-
> '/assets/brand/logo-300-002e45a4aec98fd92899838da9d5560f.png'

### 20. Webiste Name: [Oppo](https://www.oppo.com/in/)

```console
document.querySelector(".section-box .desc").style.color = "orange";
```
Output-
![](./assignment01/20oppo.png)
