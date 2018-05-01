---
layout: default
---


# How to have all your contacts on one safe place!

Keeping in touch with old fiends can be a major pain, your closest friends might be on facebook but your old coworker is on telegram, your grandparents don't bother with technology non-scene and you can only contact them on the phone.

Every service or company like facebook, Gmail, Outlook and your smart-phone are competing for being the most convenient way of keeping in touch, this endless competitions only serves to fragment your contact list. All your work contacts are on some old email account, your old college friends are somewhere in a FB group. In other words no service is truly convenient.

If you could only go back to the old days of writing down phone numbers and emails on a reliable sheet of paper everything would be better! right? well... Old school address books are inconvenient if you have to keep them in a bag somewhere handy at all times, we can do better: V-cards are what you are looking for.

V-cards are simple, small files. Easy to store on a USB stick or backed up in the cloud and they can store each and every single one of your contacts in one safe and easy to read place. That means all your facebook contacts, your smarphone address book and old emails in one place.

# What is a V-card and how to read and understand them?

So what are v-cards? well they are made in plain text for easy reading this files end in .vcf (short for v card file) and they read very much like and old school address book. For example: lets say I want to store the phone numbers of King Kong and Mario Bros, in that case I want something like this:

```
first contact begins here


king kong

cellphone number is 123...

fisrt contact ends here

second contact begins here

mario bros

home phone is 321..

second contact ends here

.
.
.
.
etc
```

We are writing this because we actually mean what's shown in the image below:

![What you mean](https://i.imgur.com/1hppDxM.png)

If you look at them side by side its very easy to see the correlation because people understand adress books and the concept of phone numbers, but computers are really dumb, they truly are stupid.

![big dumb dumb](http://techchunks.com/wp-content/uploads/2010/06/Rrror-while-creating-Error-Report.jpg)

so we have to explain to them with a bit more detail.

This is why instead of writing in the "first contact begins here" format we will write some very simple code, we will write:

```
BEGIN:VCARD
VERSION:3.0
FN:king kong
TEL;TYPE=CELL:123...
END:VCARD
BEGIN:VCARD
VERSION:3.0
FN:mario bros
TEL;TYPE=HOME:321..
END:VCARD
```

At the beginning we write <code>BEGIN:VCARD (then the enter key) VERSION:3.0</code> because that is the only way our dumb computer will understand <code>first contact begins here</code>


