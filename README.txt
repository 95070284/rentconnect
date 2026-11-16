RENTCONNECT — SIMPLE HTML + CSS

Kaise open karein
1. ZIP ko extract karo (ZIP ke andar se direct open mat karna).
2. rentconnect folder ko VS Code mein open karo.
3. index.html ko browser mein open karo, ya Live Server use karo.
Koi installation, framework, JavaScript ya internet zaroori nahi hai.

Files
index.html    Renter homepage ka content aur sections
style.css     Saare pages ke colours, spacing aur mobile layout
owner.html    Neeche List Your Property click karne par ye page khulta hai
account.html  Login/Sign Up ka placeholder design
images/       AI-generated sample room photos

Easy changes
Heading: index.html mein '2. Hero' comment dhoondo.
Photo: images/ mein apni photo rakho aur img src ka filename badlo.
Example: <img src="images/my-room.jpg" alt="Your room description">
Room/rent: 'Room 1', 'Room 2', 'Room 3' comments ke neeche edit karo.
Naya card: ek poora <article class="card">...</article> copy karo.
Colours: style.css ke start mein --teal aur --navy badlo.
Photo height: .hero-photo aur .card-photo img edit karo.
Mobile look: style.css ke '13. Mobile' section mein edit karo.
Owner redirect: href="owner.html" ko apne future owner page path se replace karo.

Important
Ye static frontend hai. Search sirf sample listings tak le jata hai; filter nahi karta.
City chips sirf labels hain. Heart checkbox sirf current preview mein toggle hota hai.
Login, account creation, photo uploads aur listing publishing connected nahi hain.
Disabled buttons is baat ko clear rakhte hain.
Real owner dashboard/backend abhi included nahi hai.
Photos generated examples hain; real property listing mein actual photos lagana.
AI photo prompt details IMAGE-PROMPTS.txt mein diye hain.

Mobile update
Header ki alag menu row, responsive photo ratio aur stacked search fields.
320, 360, 390, 600, 651, 768, 800, 1000, 1440 px viewport widths par Chromium mein layout checked.
Homepage, owner aur account pages: no horizontal overflow; images loaded; owner page link passed.
Phone ke real Safari/Chrome par bhi apne final content ke saath check karna.
