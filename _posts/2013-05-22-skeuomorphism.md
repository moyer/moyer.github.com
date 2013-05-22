---
layout: post-no-title
title: Skeuomorphism
date: 2013-05-22
---

TRYING TO FORCE A REBUILD

<img class="img-wide margin-b margin-t" src="/assets/2013-05-22-skeuomorphism-title.png">

Skeuomorphism in interfaces has seemingly reached its apex. The tide has now turned, and where it will take us has been a major topic of discussion among designers and tech bloggers.

Skeuomorphism in interfaces is the use of visual metaphors that make certain elements look like actual, physical objects. Imagine designs that employ a lot of textures, shadows, gradients, and other 3D effects, like a calendar app that looks like an actual piece of paper.

(Readers should note that I'm using the popular definition of [skeuomorphism](http://en.wikipedia.org/wiki/Skeuomorph), which is essentially a synonym for visual metaphor. The [traditional definition](http://www.themachinestarts.com/read/2012-11-how-we-started-calling-visual-metaphors-skeuomorphs-why-apple-design-debate-mess) is far narrower. )

Recently, the discussion has centered around Apple's new version of iOS. There is much [speculation](http://hypercritical.co/2013/05/03/beauty-truth-and-jony-ive) about the [expected shift](https://medium.com/thoughts-and-words/5ccef7b3e1fc) away from its current skeuomorphic look toward a [flatter appearance](http://www.simplyzesty.com/mobile/ios-7-concept-designs-welcome-to-the-future-of-the-iphone/). This change would follow a larger trend of non-skeuomorphic design that's becoming more and more popular.

While I find the speculation interesting, I think exploring the causes for such shifts is particularly useful. Skeuomorphism was a trend. And the reaction to skeuomorphic design, colloquially known as "flat" design, will also be a trend. It's hard to pinpoint and separate all of the factors that contribute to the rise and fall of design trends, but there are some conditions that stand out in this case.

## It's Not Retina

Back in January, John Gruber of *Daring Fireball*, wrote a piece titled ["The Trend Against Skeuomorphic Textures and Effects in User Interface Design"](http://daringfireball.net/2013/01/the_trend_against_skeuomorphism). In it, he theorizes that Apple's [Retina displays](http://en.wikipedia.org/wiki/Retina_Display) are causing the shift away from skeuomorphism:

> What occurs to me is that the timing of this trend, and the fact that iOS — and the iPhone in particular — is its leading edge, is not coincidental. It’s because of retina displays.

> The whole default iOS look — the textures, the shadows, the subtle (and sometimes unsubtle) 3D effects — is optimized for non-retina displays. It’s makeup to cover up the fact that 163 pixels per inch, though better than anything we had before the original iPhone, is still a crude resolution overall. Retina displays are no longer limited in such ways, and need no phony effects to create interfaces that are beautiful…

> The trend away from skeuomorphic special effects in UI design is the beginning of the retina-resolution design era. Our designs no longer need to accommodate for crude pixels.

While I like and respect Gruber, I think he's used some pretty poor reasoning to reach this conclusion.

Retina displays, for the most part, are equal opportunity improvers. They make *everything* look better. (Except [low resolution images](http://alistapart.com/article/mo-pixels-mo-problems), of course.) But if they excel in one thing, it is, by definition, displaying precise details.

Skeuomorphic designs, in almost all cases, are far more detail heavy than "flat" designs. Here's an example of a typical skeuomorphic button:

<figure><img class="" src="/assets/2013-05-22-skeuomorphism-button-skeuo.png"></figure>

And here's an example of a button more in line with current trends:

<figure><img class="" src="/assets/2013-05-22-skeuomorphism-button-flat.png"></figure>

The skeuomorphic button has way more detail: a subtle noise texture, multiple gradients, drop shadows, reflections, and highlights. The flat button is straight lines, solid colors, and unstyled text. If Retina displays were going to give a greater boost in appearance to one of these, it would be the one with more detail.

Or, inversely, the more detailed button is going to look worse on a low resolution screen. Its textures, gradients, shadows, and curves will all be poorly approximated by the fewer pixels that are available. Solid colors and straight lines render quite well, even on low resolutions.

Gruber quotes an [Erik Spiekermann tweet](https://twitter.com/espiekermann/status/180877084426637313), saying: 

> If you want good type on Retina displays, stop discussing hinting et al. Just search for faces that happen to look good. Like the old days.

He then uses this for further justification that Retina is responsible for the trend away from skeuomorphism:

> Spiekermann makes an excellent point. Fonts are emblematic of the changes in design enabled by higher resolution displays. …What looked best [were] fonts that were optimized for the screen, rather than print. Fonts like Lucida Grande, Verdana, and Georgia. Those fonts look best-of-breed on sub-retina resolution color displays, but look cheap when used in high resolution print. (Ikea, I’m looking in your direction.) On retina displays there’s simply no reason not to use any font you want. All fonts render nicely on retina displays.

But this reasoning doesn't actually support Gruber's theory.

All fonts render nicely on Retina displays because they can show the kind of detail that was previously only possible in print. You need font hinting on low quality displays because they can't render the intricate details of most fonts. That's also one of the reasons sans-serif fonts have been so popular on screen. Serifs don't look good when you only have a few pixels to render them.

Again, if Retina screens favor a certain style of design, it's heavily detailed design -- like skeuomorphism -- not minimalistic, flat design.

That's not to say that Retina displays had no influence on this trend, but if they did it's purely incidental. The arrival of a new piece of technology may end up being associated with similarly timed design trends, and those design trends may benefit from the new tech, but that doesn't mean the technology itself has influenced the trends, or wouldn't benefit another trend equally.

So if Retina isn't a major factor, what is?

## Unnecessary Affordances

People are growing up when it comes to digital interfaces. They no longer need visual metaphors to make them feel at home when using an application instead of a tangible object.

*It's a calendar app, that's why it looks like a paper calendar that sits on your desk.* Yeah, we get it.

People are better at understanding that data is separate from the form in which it's presented. Your calendar events aren't scribbled onto some physical thing, they're data that can show up on a Google calendar website, or desktop widget, or smartphone app. The need to stress that original connection to some physical object is over. Especially historical objects.

That doesn't mean that strong visual metaphors won't be used in the future. For example, imagine a calendar app where events and to-do items are represented by physical-looking blocks or tiles that you can place and rearrange using a touch screen. This effect and interaction helps you conceptualize, organize, and prioritize the things you need to do. It's a new way to work with your calendar data. But in this case, the visual metaphor is strictly informing the interaction; it's not about making you comfortable with your new non-paper calendar.

The transition period is over.

## Glass Is Flat

Touch interfaces themselves may also be contributing to the rejection of skeuomorphic design. 

When you're using a mouse and keyboard, there is another layer of interaction between you and the computer. You're pushing a physical mouse around and that in turn is controlling a pointer. The mouse cursor is the thing hitting the on-screen button.

Touch screens have removed this interface middleman. Your finger *is* the pointer. This raises the expectation that the affordances match the interaction.

Imagine there's a big, squishy-looking button on screen. Now, nobody actually thinks they're going to feel a big, squishy button when they touch the screen, but it does make certain visual metaphors' uselessness even more apparent. Because when you do push a finger against that big, squishy button, it doesn't feel like a big, squishy button. It feels like glass.

Touch screens make skeuomorphic designs feel even more out of place by furthering the disconnect between the appearance and the actual interaction. That button isn't going to feel textured, or soft, or metallic, so why bother making it look that way?

## The New Black

Perhaps the largest factor in the trend against skeumorphism is simply taste. Designers' tastes have changed and users' tastes have changed. Where once it was stylish to have things look 3D and textured and shiny, now it's not.

Skeuomorphism has become ubiquitous. Textures and gradients and reflections are everywhere. Once you hit a certain level of saturation, flatter designs begin to stand out and look unique. Once that happens, pioneers start leading the way. Some designers, companies, or products embrace new styles. They become the "cool kids" that everybody wants to copy.

What makes something popular is notoriously difficult to determine. But to say that there is one factor alone or even one factor that is mostly responsible for the trend against skeuomorphism is silly. It is the result of many factors, like the ones discussed above and many more, unknown variables.

It is equally unwise to suggest that we have somehow reached the peak of interface design. Just like fashion, architecture, industrial design, and everything else, the current trend will move on. The pendulum will swing back toward strong visual metaphors or maybe an entirely new direction.

The next trend, like this one, will be influenced by technology, necessity, and taste. And there will be pioneers to lead the way. It will likely be impossible to predict. So, if you want to see the future of software UI design, you'll have to invent it.