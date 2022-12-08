# DOM Manipulation Assignmnt Answer

### 1.  Website - [dev to](https://dev.to/)

Code - 
```console
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerText = "Vidya Sagar Mehar"

document.querySelector(".side-bar .crayons-card p").innerHTML = "I write code"

```
Output - 

Changes "DEV Community 👩‍💻👨‍💻 is a community of 925,602 amazing developers" to Name-  "Vidya Sagar Mehar" passion = " I write code".

![01DevTo](https://user-images.githubusercontent.com/92782806/206519633-80eacae1-f63b-4569-85fb-4a5876aa1c67.png)



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

![03youtubeOutput](https://user-images.githubusercontent.com/92782806/206519910-457b49c8-a37f-4f7c-83a9-4257794019a5.png)



### 4. Website [Oneplus](https://www.oneplus.in/support)

Code -
```console
document.querySelector(".customer-support .service-number").innerText = "+91 77177 67744"
```

Output -

Changed phone no. to my Mobile no.

![4oneplus](https://user-images.githubusercontent.com/92782806/206520232-4e1fd55b-391e-4856-820d-92951f2f3970.png)



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

![05samsung](https://user-images.githubusercontent.com/92782806/206520292-9c9ba533-4130-4e04-99de-cf4057106685.png)



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

![06search](https://user-images.githubusercontent.com/92782806/206520386-86e90297-3c8b-4357-a621-65cb4209385d.png)


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

![07MDN](https://user-images.githubusercontent.com/92782806/206520472-a6977ff9-630c-49ea-b585-0b60f0ef7486.png)


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


![08google](https://user-images.githubusercontent.com/92782806/206520550-915865d5-b702-449b-8e51-c2a7753d7c40.png)



###   9. Webiste Name: [Code Wars](https://www.codewars.com/)

Code -
```console
document.querySelector(".content-width-extra-large .display-heading-1").style.fontFamily = "serif"

document.querySelector(".content-width-extra-large .display-heading-1").style.color = "#8B2E1D";
```

Output -

![09codewars](https://user-images.githubusercontent.com/92782806/206521027-0c2e60de-46e6-4978-8c4e-d1ea1b19992e.png)


### 10.  Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

Code -
```console
function changeBG(){
    document.querySelector(".btn-cta-big .login-btn-text").style.backgroundColor = "red";
};

document.addEventListener("click", changeBG)
```

Output -

![10codeCamp](https://user-images.githubusercontent.com/92782806/206521080-e91b740e-e0fd-4bbd-95b8-2b2265424a67.png)


###   11. Webiste Name: [realme](https://www.realme.com/in/)

Code -
```console
document.querySelector(".wrapper .gtag .icon-logo ").style.backgroundImage = "url(https://ineuron.ai/images/ineuron-logo.png)";
```

Output -

![11realme](https://user-images.githubusercontent.com/92782806/206521124-cb69c1e2-e038-47e7-9bb0-6d9d590c3483.png)



###   12. Webiste Name: [Github](https://github.com/)

Code -
```console
document.querySelector(".js-repos-container h2 a").style.backgroundColor = "blue";
```

Output -

![12github](https://user-images.githubusercontent.com/92782806/206521160-dadd9a62-c7d8-4b1c-8b91-0f1384966481.png)



###   13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

Code -
```console
document.querySelector(".fl-module ").innerHTML = "JSBOOTCAMP"
'JSBOOTCAMP'
```

Output -

![13hackerrank](https://user-images.githubusercontent.com/92782806/206521218-999c9457-6d42-4e8a-b4e2-0e6a065d287d.png)


### 14. Webiste Name: [Asus](https://www.asus.com/in/)

Code -
```console
document.querySelector(".HotDealsAll__Heading__2fIbe").style.fontSize = "100px";
'100px'
```

Output - 
![14Asus](https://user-images.githubusercontent.com/92782806/206521301-8c6ec9b0-61e0-4a41-9914-f68ea7ad61ca.png)



### 15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

```console
document.querySelector(".ps-title a").style.textAlign = "right";
```
Output-

![15dell](https://user-images.githubusercontent.com/92782806/206521405-4e7fc6a9-ea6c-4b5a-acab-b14a66002177.png)


### 16. Webiste Name: [Vercel](https://vercel.com/)

```console
document.querySelector(".section-title_title__VEDfK").innerHTML = "Start with Scratch"
```
Output-

![16versel](https://user-images.githubusercontent.com/92782806/206521458-7366591a-12f8-4698-8f34-a083b0cf7d63.png)


### 17.Webiste Name: [Sony](https://www.sony.co.in/)

```console
document.querySelector(".btn-container a").innerHTML = new Date();
```
Output-

![17sony](https://user-images.githubusercontent.com/92782806/206521503-40519a25-4315-4670-ab8a-07ffadd61b15.png)


### 18. Webiste Name: [Philips](https://www.philips.co.in/)

```console
document.querySelector(".p-footer").style.backgroundColor = "orange";
```
Output-

![18philips](https://user-images.githubusercontent.com/92782806/206521543-d50f5d2b-388a-4d00-bc77-35cff1505a12.png)



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

![20oppo](https://user-images.githubusercontent.com/92782806/206521640-c236ac08-7e82-43fa-813b-97bdf03ac89f.png)

