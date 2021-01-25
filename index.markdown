---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
whatsapp_text: Hey there. I am inquiring about your courses.
---

**Our Courses**

| Office Basics | MS-Access | CCC |
| C | C++ | JAVA |
| Dot Net | Python | Database |
| English Typing | Hindi Typing | Networking | 
| Spoken English Classes| Urdu Classes |

---
**Contact Us**

|----------------+-------+---------|
| Phone/WhatsApp | Email | Address |
|----------------+-------+---------|
| {{ site.phone }} [Call](tel:{{site.phone}}) [WhatsApp](https://wa.me/{{ site.phone | remove: "+" | remove: "-"}}?text={{page.whatsapp_text}}) | [{{ site.email }}](https://mail.google.com/mail/?view=cm&fs=1&to={{ site.email }}&su=Query for&body=Hello Team){:target="_blank"} | [{{site.address}}](https://goo.gl/maps/9WmVvU48Tw9Wdxc97){:target="_blank"} |
