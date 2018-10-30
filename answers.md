1)

test = document.querySelector(".profile-image")
test.src = "https://placebear.com/g/400/400"

leftimage = document.querySelector("#left-image img")
leftimage.src = "https://placebear.com/325/225"

2)

h1 = document.querySelector("h1")
h1.innerText = "Kevin"

3)

employment = document.querySelector("#employment h3")
employment.innerText = "Work Experience"

4)

bodycolor = document.querySelector("body")
<body>​…​</body>​
bodycolor.style.backgroundColor = "darkorchid"


5)

highlightcolor = document.querySelectorAll(".highlight")
for (var i = 0; i < highlightcolor.length; i++) { highlightcolor[i].style.backgroundColor = "grey";}

6)

font_family = document.querySelector("h1")
<h1 class=​"highlight" style=​"background-color:​ grey;​">​Panda The Bear​</h1>​
font_family.style.fontFamily = "monospace"

7)

anchor_color = document.querySelectorAll(".action-icon-bg")
for (var i = 0; i < anchor_color.length; i++) { anchor_color[i].style.backgroundColor = "blue";}

8)

form_name = document.querySelector('form #name')
form_name.placeholder = "identify yourself"

9)

form_message = document.querySelector("form #message")
form_message.placeholder = "state your business"

10)

form_name = document.querySelector('form #name')
form_name.value = "your nemesis"

11)

form_email = document.querySelector("form #email")
form_email.value = "koalathebear@gmail.com"

12)

form_submit = document.querySelector("form #submit")
form_submit.value = "En garde!"

13)

form_submit.disabled = "true"

14)

textinfo = document.querySelectorAll(".bio-info-value")
for (var i = 0; i < textinfo.length; i++) { textinfo[i].innerText = "";}
