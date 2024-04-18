
# ModalWhatsApp ReactJs

ModalWhatsapp-ReactJs is a component designed to facilitate the creation of URLs that redirect to the WhatsApp API. You just need to fill in the necessary fields, and it will do all the work for you.

![Desktop-18-04-2024-12-07-29](https://github.com/MSarpi/ModalWhatsapp/assets/81937827/6a1619e1-9fb2-40f0-8648-c7ea119322e8)

# Installation 
1. First, you must install npm.
```
npm i modalwhatsapp-reactjs
```
2. Once installed, you should import the dependency into the file where you want it to be used (if you want to avoid issues when running it, it's better to add it in the main file of your project).
```py
import WhatsappModal from 'modalwhatssapp'
```
3. When it's already imported, you just need to add the import name with <*package name*/> and include the fields needed to customize both the button, modal, and redirection link.

It should look like this:

![asdsad](https://github.com/MSarpi/ModalWhatsapp/assets/81937827/f6d3d161-5a3a-4f3b-990d-a0649be3774e)

Here is the code for you to add to the component:
```py
    btnText='button whatsapp' // Button text
    btnBackground="#00695c" // Modify button color
    btnColorText="#fff" // Modify button text color
    sizeY="140px" // Modify height
    sizeX="240px" // Modify width
    bgColorTop="#00695c" ////Modify top background color
    bgColorBottom="#00695c" // Modify bottom background color
    btnResponse="respond" // Text to respond to the toast or modal
    business="company" // Company name or portfolio name
    businessColor="#ebebeb" // Company text color
    message=" hello, do you need help?" // Message that goes in the modal
    phone="56999999999" // Telephone number, this will redirect to the Whatsapp API
    textLink="I am a link text" //Custom message that goes in the Whatsapp API redirection
```

And with this, you would already have a functional button that redirects to your WhatsApp number! Here's a real example:

![Desktop-18-04-2024-12-49-19](https://github.com/MSarpi/ModalWhatsapp/assets/81937827/f52a5488-2bd7-4703-9a9a-aac2bb4372de)

# Created by SarpiDesign.
### If you have any doubts or questions, please contact directly at: *Miguel.sarpi@gmail.com*
