---
layout: post
title: "Passwords"
description: "Passwords, Managers, 2FA"
image: images/post3.jpg
tags:
  - Easy
note: "\"p@55w0rd\" is a bad password"
---

# Generate a Great Password

Most people have the same password, or variations of the same password, for every website/app. This is more convenient, as you don't have to remember something new for every website you use. Consider this, however:

An online ticket selling website is hacked and your email and password are stolen. Joe Hacker can now gain access to your:
* Bank account
* Social media
* Amazon account
* Your email account (this would allow them to lock you out of everything)

Sure, having your password as `helloAmazon1` for Amazon and `helloInstagram1` for Instagram seems more secure, but if someone figures out your "formula", you're done for.

## What Can You Do?

Creating more secure passwords is easy. Simply create an algorithm that you can plug each website or service into to get your password. I'll walk you through an example:

### Pick a Sentence or Phrase

Let's say you love Shakespeare. We'll pick a sentence from Othello.

>  “Thou weigh'st thy words before thou givest them breath.”

<cite>William Shakespeare</cite> --- Othello, 1603
{: .small}

We'll take the first letter of every word to be our base.

**T**hou **w**eigh'st **t**hy **w**ords **b**efore **t**hou **g**ivest **t**hem **b**reath

### Capitalize Certain Letters

We'll go with the number of consonants in the website name. We're currently on Amazon, so our password now becomes:

> twTwbTgtB

There are 3 consonants in "Amazon", so we capitalized every third letter.

### Add Some Numbers

We'll add the number of syllables to the beginning of the password.

> 3twTwbTgtB

There are 3 syllables in "Amazon", A-ma-zon, so we added a 3 to the beginning.

### Add a Special Character

We'll add a $ to the position that corresponds to the number of vowels.

> 3t$wTwbTgtB

There are 3 vowels in "Amazon", so we added a $ to the third location of the word.

---

We now have a unique, and seemingly meaningless password for Amazon. We can rinse and repeat this formula for all of our other services, as long as we have:

* Our phrase from Shakespeare
* The website/app name
* Our 3 rules

## Still Too Complicated?

You should use a password manager. Password managers will store (and hopefully encrypt) all your passwords and autofill them for you, provided you enter your "master password".

We recommend [LastPass](https://www.lastpass.com/business-password-manager) because they have plugins for all the top browsers, as well as mobile apps for iPhone and Android. They are free (for personal use, not business use), secure, and easy to use.

Use your algorithm once and let your password manager remember this for you. Make sure your master password is secure, however, because if someone figures that out, all your passwords are accessible.

## 2FA

Along with having a strong, unique password, you should consider setting up 2-Factor Authentication (2FA). This will require one extra step to signing in to a website or app, but it provides additional security. If someone were to get a hold of your password, they couldn't login to the website without having your phone and the 2FA code as well. It's highly unlikely that they will have both your password and phone, so you can simply change your password and move on.

### How Does It Work?

You'll enter your username and password as usual, but then you'll be asked for a 6-digit code that is randomly generated by an external app.

### How Do I Get 2FA?

There are different 2FA apps you can use, but some websites only work with some services. I've found that **Google Authenticator** and **Authy** cover the majority of services out there.

> When you link a 2FA account, make sure to keep a copy of the code or QR-Code that they provide you, because this will enable you to relink on a different device. If you don't keep track of this, you will **not** be able to access your account.

Once again, **keep a record of the codes you used to setup each of your 2FAs.**

---

Congrats! You now have an easy way to generate and remember unique passwords, a password manager to do the heavy lifting for you, and 2FA to protect you even further. Time to go update all your accounts.
{: style="text-align: center;"}