# Monthly Expense Tracking Application with JS

![Gider Takip Uygulamasi](https://github.com/kaplanh/Aylik-Gider-Takip-Uygulamasi/assets/101884444/5383ad7b-22cd-49c0-a391-9736c52d1ab1)

[Click Me!](https://kaplanh.github.io/Aylik-Gider-Takip-Uygulamasi/)

## Description

The project aims to create a Monthly Expense Tracking Application using JS and Bootstrap.

## Problem Statement

- Your company has recently started on a project that aims to create a Monthly Expense Tracking Application. So you and your colleagues have started to work on the project.

## Project Skeleton 

```
Monthly Expense Tracking Application (folder)
|
|----readme.md                        
|----index.html  
|----style.css
|----app.js
|----images (folder)
``` 


### At the end of the project, following topics are to be covered;

- HTML
   ```
   -font-awesome cdnjs link
   <link
            rel="stylesheet"
            href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
            integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
            crossorigin="anonymous"
            referrerpolicy="no-referrer"
        />
   - for Bootstrap cdnjs link
    <link
            href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
            rel="stylesheet"
            integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM"
            crossorigin="anonymous"
        />
   - for sweetalert script
     <script src="https://cdn.jsdelivr.net/npm/sweetalert2@10"></script>
   Swal.fire({
             icon: "warning",
             title: "DiKKAT",
             text: "Verileri silmek istediginizden emin misiniz?",
            })
   ```
 
- CSS
  ```
  - background
     body{
     background-image: url('./images/backgroundImg.jpg');
     background-repeat: no-repeat;
     background-size: 100% 100%;
        }
  ```
-Bootstrap
 - Bootstrap form
 - Bootstrap table
 - Bootstrap Grid (Row-Col)
  
  

- JS
  - DOM Manipulations
  - DOM Selectors
     - querySelector('#id')
  - Events
     - load
     - click
     - submit
  - Builtin functions
     - preventDefault()
     - reset()
     - remove()  
  - if else - if - else conditions
  - Logical operators && and ||
  - LocalStorage
     - localStorage.setItem("variable", primitiveValue)
     - localStorage.getItem("variable")
       
     - localStorage.setItem("variable", JSON.stringify(nonPrimitiveValue))
     - JSON.parse(localStorage.getItem("variable")) || []
  - Date()
     - new Date().getTime()
     - dateInput.valueAsDate = new Date();//Tarih inputunu bugunki tarih ile yukle
   
  - Array Methods
     - harcamaListesi = harcamaListesi.filter((harcama) => harcama.id != id);
     - Arr.forEach((item) => harcamayiDomaYaz(item))
     - Arr.reduce((toplam, harcama) => toplam + Number(harcama.miktar),0);
  - Capturing
     - e.target.classList.contains("fa-trash-can")//tiklananlardan class'i fa-trash-can olanlari yakala.
     - e.target.parentElement.parentElement.remove(); //parent'inin parentini sil.
  -confirm()
     - if (confirm("Silmek istediginize emin misiniz?"))

    

### At the end of the project, developers will be able to;

- improve coding skills within HTML, CSS and JS 

- use git commands (push, pull, commit, add etc.) and Github as a Version Control System.


## Notes

- You can use HTML, CSS, Bootstrap and JS to complete this project.



<p align="center"> ⌛<strong> Happy Coding </strong> ✍ </p>


