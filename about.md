---
layout: page
title: "About"
description: "This is what ePosition is."
header-img: "img/about-bg.jpg"
---

# What is Your Name in IoT? 

Remember [Inspector Gadget](https://www.youtube.com/watch?v=e-JHfXVlkik), a famous television animation shown in the early 2000s? All sorts of tools like propellers and magnifying glasses come out of his hat, robot arms stretch to grab the bad guys, and his dog is smart enough to understand human language! 

Man, when I was a kid, I wished for those gadgets for my birthday.

It has been only about 15 years since the animation was released, but now we already have so many gadgets around us, including our smartphones or popular fitness trackers. The rise of the Internet of Things(IoT) will dramatically increase the number of “things” connected to us in the near future.

## The concept of “things” is expanding 


In the hyper-connected IoT, not only smart objects, but also we, the humans, are connected to the Internet and produce tons of data from the sensors attached to us.

Just by carrying a smartphone, I produce personal data about my motions, locations, music preferences, writing patterns, and so many more. In the near future, wearables will record my health data, and smart hub at my home will recognize my lifestyle. All these personal data will be saved somewhere in the cloud, waiting to be processed as useful information.

Then, can I be considered as one of the trillions of “things” connected to IoT? Aren’t I producing data and communicating with other “things” in a same way as other “things” do in the network?

The famous tech guru, Tim O’Reilly also says in [his writing](https://www.youtube.com/watch?v=e-JHfXVlkik),

> It really ought to be called the Internet of Things and Humans — #IoTH, not just #IoT! — Tim O’Reilly

## Are we naming “things” for #IoTH or just #IoT? 


As millions, billions of “things” and “humans” are being connected to the Internet together, there is no doubt that naming and identifying each object is one of the most important concepts of this network. 

But are we naming “things” in a right way for the expanded Internet?

[The Physical Web](https://google.github.io/physical-web/), a IoT project recently initiated by Google, wants to attach **URL**s  to “things” as their names. Both [IoTivity](https://www.iotivity.org/documentation/linux/programmers-guide/registering-resource) and AllJoyn, IoT platforms respectively started by [Open Interconnect Consortium](http://openinterconnect.org/) and [Allseen Alliance](https://allseenalliance.org) with a common goal of becoming standard, assign **URL-style names**(ex. oc://192.168.1.1:5683/light/1) to “things”. 

We are familiar with URLs to locate all resources in the Web. Maybe that is why the idea of using URL as the identifier is taken for granted. 

Websites have been the primary components of the Internet. Therefore, most people perceive typing in a URL on a browser as connecting to one of them.

However, IoT is different. The connected “things” are not websites but smart objects like our smartphones or cars. Would you use a URL to access your phone, your car, or your watch?

## So how should we name“things”? 


In the Internet of Things, identification was enough by being machine readable like URLs. However, in the “Internet of Things and Humans”, the identification should be both closer to the human language and readable to machines.

So, let me introduce **ePosition**.

ePosition is a [Univeral Resource Identifier(URI)](http://en.wikipedia.org/wiki/Uniform_resource_identifier) that every “thing” in IoT owns an email-like address type of identification. Instead of @, it uses #. 

For example:

<p style='text-align: center;'>
Myself = <b>me#parkjiho.kr</b>
</p>

<p style='text-align: center;'>
My phone = <b>myphone#parkjiho.kr</b>, 
</p>

<p style='text-align: center;'>
My laptop = <b>mac#parkjiho.kr</b>
</p>
<p style='text-align: center;'>
The Pepsi vending machine at Timesquare 

= <b>timesquare1#pepsi.com</b>
</p>
<p style='text-align: center;'>

Robot Arm of Inspector Gadget

= <a href="http://en.wikipedia.org/wiki/Uniform_resource_identifier"><b>robot-arm#inspector-gadget.me</b></a>
</p>
<p style='text-align: center;'>

Artwork at Museum of Modern Arts 

= <a href="http://www.moma.org/interactives/exhibitions/2014/matisse/the-swimming-pool.html"><b>matisse-the-swimming-pool#moma.org</b></a>
</p>
ePosition enables users to communicate with “things” as we do with other people through email. It breaks the convention of URLs and thus embraces the expanded concept of “things” in IoT by naming closer for both humans and computers.

ePosition’s email-like identification is not a totally new concept, but many IT companies have implemented a similar way of identification and communication. Amazon and HP have assigned emails to [Kindle](http://www.amazon.com/gp/sendtokindle/email) and [printer](http://en.wikipedia.org/wiki/HP_ePrint) to send documents to the device.

Humans will more and more communicate with objects like as they do with other humans. For example, [LG has introduced HomeChat](http://www.lg.com/ae/press-release/lg-rolls-out-premium-smart-appliances-that-chat), which enables users to communicate with smart appliances through a messaging app. 

![LG HomeChat](/img/homechat.jpeg) 

LG Homechat. Pic from CNetImagine each device having its own ePosition address. All you (**me#my-home.com**) need to do is know its address (ex. **air-cleaner#my-home.com**) and communicate within the phone via browser or messaging apps like WhatsApp after adding the ePosition address.

Or think about M2M communication. My home-hub (**home-hub#revolv.com**) give orders to the robot vacuum cleaner (**vacuum-cleaner#samsung.com**) by simply sending message like an email. There is no need for dichotomy in Machine-to-Machine and Human-to-Machine communication.

Furthermore, ePosition is easier for natural language processing than URL with simpler syntax, more independent, unique choice of naming in different domain, and has multi-language support(to be implemented with Unicode). Also, think about how ePosition will make IoT easier for developers.

## Interested in ePosition?  

Now ePosition is currently patented and is on research by a startup called ePosition Korea, working with researchers from Korea Advanced Institute of Science & Technology (KAIST). 

We still have incomplete steps for adapting ePosition to the industry, but we would like to hear from the tech community about what you think about this idea.

What do you think about ePosition? Send us an email or comment on this post. Or mention us on Twitter!

*Orginally posted on [Medium.com](medium.com)*
