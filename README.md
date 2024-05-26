# Destructors
Destructors ka kaam object ki lifecycle khatam hone par resources ko free karna hai. Yeh khas taur par dynamic memory allocation ke sath important hotay hain, jahan aapko manually memory free karni parti hai.
Destructors ke Bare Mein Kuch Ahem Baten:
Definition: Destructor ek special member function hota hai jo object destroy hone par automatically call hota hai.
Syntax: Destructor ka naam class ke naam ke aage ~ (tilde) symbol lagane se banta hai.
Parameters: Destructors koi parameters accept nahi karte aur na hi return type hota hai.
Default Destructors: Agar aap explicitly destructor define nahi karte, to compiler ek default destructor provide karta hai.
Usage: Destructors ko khas taur par dynamically allocated memory, file handles, aur other resources ko release karne ke liye use kiya jata hai.
