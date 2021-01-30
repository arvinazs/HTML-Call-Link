# HTML-Call-Link
Create a click to call link HTML only

First create a **standard** link tag with your phone number inside of **href** attribute

like this...

```
<a href="+91-2959292702"></a>
```
###### *Don't forget to add +country code then number*

---

Now to make it work,just add **tel**: before the number

like this..

```
<a href="tel:+91-2959292702"></a>
```
---
Add some text as a custom 

like this...

```
<a href="tel:+912959292702">
  Call us at +912959292702
</a>
```

---

And Don't do this mistakes

*Forgetting **quotes** in the HTML*

*using **dashes***

*Forgetiing to place a **colon** after "tel"*
