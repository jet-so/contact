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

first contact ends here

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

If you look at them side by side its very easy to see the correlation because people understand adress books and the concept of phone numbers, but computers are really dumb, they are truly stupid.

![big dumb dumb](http://techchunks.com/wp-content/uploads/2010/06/Rrror-while-creating-Error-Report.jpg)

So we have to hold their hand and explain them what we want them to do in the simplest way possible, meaning we have to write some code.

This is why instead of writing in the "first contact begins here" format we will write some very simple code, we will write:

*(using capital letters on the code is necessary)*

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

At the beginning we write <code>BEGIN:VCARD (then the enter key) VERSION:3.0</code> because that is the only way our dumb computer will understand <code>first contact begins here</code> and at the end we write <code>END:VCARD</code> because it means <code>first contact ends here</code>.


<code>FN:</code> is short for "**Full Name**", <code>TEL;TYPE=CELL:</code> means **This is a cellphone number** and <code>TEL;TYPE=HOME:</code> means **This is a home number**.

Vcards support saving their email, were they work at, their position, their website, birth dates and much more.

For your continence I have created a simple template that explains each type of information you can store.

The princes is on another castle  

# V-card template

```
BEGIN:VCARD
VERSION:3.0
N:Lastname;Surname
FN:FULL NAME GOES HERE
ORG:ORGANIZATION GOES HERE
URL:WEBSITE GOES HERE
EMAIL:EMAIL GOES HERE
TEL;TYPE=CELL:CELLPHONE GOES HERE
TEL;TYPE=HOME:HOMEPHONE GOES HERE
B-DAY:YYYY-MM-DD
NOTE:Here you can write any notes, Using "N:" is not mandatory. Coppy paste this in a text file as much as you want. Remember to save as "NAME.vcf".Order doesn't matter. Begin and end with "BEGIN:VCARD VERSION:3.0 and END:VCARD" Keep this as a reminder to you in the future. More info on the website https://archive.li/tZGj4#selection-441.10-441.20 or https://alejandroescalantemtz.github.io/blog/contacts.html or the wikipedia article on https://en.wikipedia.org/wiki/VCard
END:VCARD
```

# How to make your own V-card

## General instructions.

just copy paste the preset or start from scratch if you want on a plain text file and fill in the desired information, you can have multiple vcards inside one file, just make sure to save the document as "NAME.vcf", were you can write any title you want.

## Specific instructions with pictures.

The process on a windows computer will look like this:


First create a new simple text document like this. 

1. Go to your desired destination to save your vcard
2. right click
3. click on "New"
4. click on " Text Document"

My computer is in Spanish so your process will be on your language.

![new text file](https://i.imgur.com/gBN0Tgu.png)

5. Next you want to paste my preset and fill it in with your desired info, remember you can coppy paste it multiple times to store multiple contact on one single file, like shown below

![written vcard](https://i.imgur.com/r2JXPHJ.png)

6. then click on the save button and name your vcard, I named mine "my contact list" 

![name the document](https://i.imgur.com/43IC9vc.png)

7. then on the menu below the name box you will find a document type box, make sure to select "All documents (\*.\*)"

![save as .vcf](https://i.imgur.com/eQRE8VH.png)

8. Once saved, you will see the icon change and it will look like this:

![final step](https://i.imgur.com/BkTmPbe.png)
