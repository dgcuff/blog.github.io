---
layout: post
title:  "Naming for the future"
date:   2022-08-22 12:30:00 -0400
tags: names naming parent-child class instance
category: communication
---
How we ended up here: There is never enough time.

Software evolves over time. When writing the software, a developer creates a simple object and calls it Provider. Later, there's a need for another object quite similar to Provider, so the harried developer takes most (but not all) of the attributes of the object Provider and creates a class. Which the developer also calls Provider. There's no time to think of another name, and even if there were all the time in the world, the developer might not see a need to apply a better name.

So now we have the class called Provider, and an object within that class, also called Provider. To which the developer then adds the second object (in the same class) called Reseller. Remember, the need for the second object is what caused the developer to create a class.

If you name a class and its object the exact same thing, that will cause the computer no issues at all. (Depending on the language you're using. It's not as though creating an object without a class is great programming practice, but this blog is about technical writing, not programming.) The computer will neither blink nor hiccup and yet will never confuse the two. How could it? One's a class, and the other is an object. You humans are so dumb.

But the identically named class and object will eventually cause issues for the user. If the classes and objects are exposed in a programming interface, the user will have issues distressingly soon.

If the classes and objects are completely hidden from the user, the technical writer will have the issues first, but the user will likely have the same issues eventually. The primary issues will be understanding what the heck is going on in the first place, and keeping it straight as time goes by.

Naming a class and its object the same thing causes comprehension issues for human beings. Even the person who created the class and the object may not remember which attributes were created for which, so it's not as though these are issues only for the weak-minded.

Let's take this naming discussion away from technology for a moment. Let us suppose that you have a spouse, and that the two of you decide to have offspring. So your relationship has a new concept to consider: offspring.

Let us further suppose that you and your spouse find yourselves blessed with offspring of a kind not exactly unusual, but still not the everyday: you have fraternal twins; a boy and a girl.

Finally, let us suppose that you and your spouse agree on the following names for your offspring: Samantha for the girl, and Offspring for the boy.

"Please meet my offspring," you might say to a visitor, "their names are Offspring and Samantha."

Or how about this more common example:

You have chosen to live in a city. The city is large enough to have more than one neighbourhood. The older neighbourhoods may have names that indicate the original use for the land: Singh's Farm. Harbourside.

Newer neighbourhoods may have been built on land that were never used or cleared before. So the (land) developer names the neighbourhood (or the subdivision, if that's a more familiar term) after the principal road: Mill Stream Drive lends its name to the Mill Stream neighbourhood.

If you choose to live in a new neighbourhood, you may find yourself giving potential visitors repetitive answers:

"What part of the city are you living in?"

"Mill Stream."

"That's a nice area. Which street?"

"Mill Stream."

Confusion is eventually going to arise, I promise you. I make this promise as someone who has lived in two such neighbourhoods. 

In this fictional neighbourhood of Mill Stream, I tend to find lodgings just off the main street, which side street we will call Temple Lane. Let's say I reside at number 47. Eventually a delivery driver with incomplete records or a visitor with an imperfect memory will complain that I wasn't home as promised... because they retained the number 47 and the name Mill Stream, made the incorrect assumption that I was on Mill Stream Drive, and knocked on the door at 47 Mill Stream Drive, where no one was home. While I sat impatiently at 47 Temple Lane, waiting for their arrival.

Using the name Offspring for your offspring is not a best practice. I am not aware that this has ever happened.

Using the name Mill Stream for a neighbourhood and a road is not a best practice. I could not swear that it has happened with "Mill Stream," but it happens under other names much too frequently.

Using the same name for a class and its objects is not a best practice, and it has happened more times than I can count.

I've already explained how we got here: there's never enough time.

Now, where exactly are we?

A developer has given exactly the same name to two separate concepts, and you as a technical writer have been tasked with explaining both concepts to those users of the software who read the product documentation.

Believe it or not, all that was the preamble. What to do in this situation is the topic for a whole other entry.
