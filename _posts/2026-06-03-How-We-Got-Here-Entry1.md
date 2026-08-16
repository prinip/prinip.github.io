---
layout: post
title: How We Got Here
description: " "
---

Hi. Welcome to my little corner of the internet. You might be asking, *Well, what the heck even is this?*, and I'm here to answer that. Before I say anything else, I just want readers to know that I kinda suck at English, so if somebody reading this doesn't understand something, uh, hit me up on Discord ig? Anyways, let's get to the Story.

So it's 2023. 11-12 year old me was running free Minecraft Servers on Aternos. At this time, Freenom (which offered domains such as .tk, which is Tokelau's ccTLD if you didn't know) basically got sued to **HELL** by people such as Meta, in part thanks to the domains being used for scams, given that they're free, forcing their Domain Registrar services off the internet, through if I remember correctly (do **NOT** take this as a fact by the way) Freenom's website is still up, just that literally nothing works on the site. 

At this point in my life, I was looking for domains for (*presumably*) my *epic* SMP server, UltraSMP. As we've discussed, Freenom was *dead*, and I couldn't find any other free domain registrar services, with the exception of some Ukrainian Domain Registrar, through from my knowledge I've never gotten to even registering on it. 

I eventually found https://nic.eu.org (actually **GOATED** people, been running it since ye old '96), unfortunately, (but with full respect), the website was  clunky, through I eventually managed to register an account, I registered for the domain "ultrasmp.eu.org" with the NS (nameservers) pointed to galileo.aternos.org and columbus.aternos.org. (basically, the nameservers that Aternos owned, through at this time my young ass head didint know what a nameserver was)

It eventually made a request, but I did NOT expect it to take THIS long for the volunteers (which imo is fine, this is a **volunteer** run service) to accept my request, and if I'm being honest, I never even expected to ever get the domain, and due to the lapse of time (which was 3 years), I eventually forgot about it.

Faat forward to 3 years later. It's like June 2, 2026. I just came back home from a massive clean up drive my High School decided to do because the Academic Year was fast coming. I checked my notifications, and then I got a weird Email from a certain noreply email telling me that my domain of "ultrasmp.eu.org" had just been registered and that the domain will be propogated with 12-24 hours time.

<figure style="text-align: center;">
  <img src="/assets/Screenshot_20260603_201158.jpg" alt="Description" style="width: 300px;">
  <figcaption>The aforementioned Email.</figcaption>
</figure>

At first, I was like *"What the hell?"* and almost immediately spun up a new Aternos account to test. Sure enough, it worked, but, at this point, I basically didn't play Minecraft as much or even once since ateast 2024.

I immediately than began looking into moving my nameservers into Cloudflare (which offer a Free Tier of their Enterprise Grade Domain Control and Protection) and then from there hopefully route a subdomain (the domain **YOU** are on right now is **THAT** subdomain) to redirect to a Github Pages personal website, due to me wanting to still use the main domain for Aternos.

I managed to change the Nameservers to Cloudflare's own Nameservers, with Cloudflare going absolute **HAM** looking for existing DNS Records, sure enough, it found 6 A records, a SRV record (which was ***critical*** for the Minecraft part of the domain), and tons of leftover NS records. I cleaned out the records, essentially nuking all of the existing NS records, retaining the 6 A records and single SRV record, all via DNS Only. Within 15 mininutes after changing the nameserver, Cloudflare picked it up, and now I officially had Enterprise Grade web tech powering my site.

I immediately configured a Github Pages site and then using a CNAME record, I pointed it to blog.ultrasmp.eu.org, and the fruit of all that, is what you're seeing right now.

Now, you might be curious as to **WHAT** Mr. Jeffrey Prinipstein is going to do with this blog and domain, respectively, and actually it's kinda simple on the topic of what to do in the Blog. 

Of course, being that this is a blog (and I've already put it on the welcome description of this site), I will be posting wildly different things, ranging from nerdy things such as DXing and configuring Homelabs, to actual IRL politics (I am planning to make my second blog post a overview or rather maybe a expose or worse rant about a Political Party, through I'm not sure if that will **EVER** come into fruition).

On the domain side, I'll probably be using my other subdomains to create my own server, through Homelab isnt an option for me, because of our house being small. I did want a Oracle Always Free VPS, however, it needs a card, and given that you could infer my age range from this post, I don't HAVE a card, but I will see through my options.

This blog post also served as my testing to get used to typing in Markdown, the process to get things working with Cloudflare, Github Pages, etc., has been **PAINFUL** but I think what I have finished with, is what I really wanted for a personnal blog site.

Thanks for reading, cheers and 73! Pop the champagne :)
