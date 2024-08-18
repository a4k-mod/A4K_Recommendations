# FAQ

For your convenience, we have compiled a list of some frequently asked questions to help you find answers quicker.

## What's with all the buffering?

Kodi add-ons interface with content already made available online, they have nothing to do with the distribution of content whatsoever. Poor playback quality is something that every Kodi user will encounter sooner or later when using these websites. This poor playback may involve choppy video which might mean your hardware device can’t handle the video quality or the encoding of the stream itself is corrupt. Another issue may be constant buffering. Both of these issues really are something that are entirely out of developers' hands. Causes of Buffering

- Stream Source Slowness – sources are powered by servers, servers are connected to networks. These sources are providing free service and sometimes have limitations set in place as a result.
- Peak Time Congestion – certain times of day are busier on the internet than others. If you’re talking about a Sunday or Monday night, those are probably busier times for internet use in general, meaning this could affect the source’s network speed, or even your internet connection locally.
- Geographical Location – Believe it or not, servers have physical locations and some places on Earth aren’t as well connected as others. Depending on where you’re located, your connection to the source’s servers could be impaired.
- Internet Connection Speed – your internet connection might just be too slow to support video streaming.
- Hardware Issues – your router might not have strong enough wireless power, the cheap no-name modem your service provider gave you might be defective, or your streaming device might not have the latest firmware installed.
- Advanced Settings XML – generally speaking, modifying this file will not solve buffering issues and will likely cause more trouble than anything, such as device crashing because the custom buffer size is larger than the device can handle (Kodi already allocates 300% of the memory to the buffer size). It is only useful in the rare event that you see the “Cache Full: Cache filled before reaching required amount for continuous playback” notification.

### Possible Solutions

- Hardware Reboot – reboot your modem and router by unplugging them for five minutes or so, then do the same with your streaming device.
- Debrid Services – through a single paid subscription to Real-Debrid or Premiumize, these services allow you to take advantage of the premium services offered by dozens of sources. This will decrease buffering by giving you access to premium bandwith offered only to paid users.
- Update Kodi – if you’re using an older version of Kodi, it could likely result in less efficient streaming, it’s always a good idea to update to the latest stable version.
- Update the addon – if you’re using an older version of the addon, it could likely result in less efficient streaming, it’s always a good idea to update to the latest stable version.
- Update URL Resolver – if you’re using an older version of URL Resolver, it could likely result in less efficient streaming, it’s always a good idea to update to the latest stable version.
- Hardwired Ethernet – depending on the size of your home or building materials, you might experience wireless connection trouble, this can be fixed by hardwiring an ethernet cable from your router directly to your streaming device.
- Internet Connection Speed – call your internet service provider and upgrade your connection speeed, do your own speed test beforehand.
- Hardware Upgrades – if your streaming device is really old, you might want to consider purchasing a newer one. It might also be a good idea to look into a new, faster router, as those things aren’t built for life either.
- Modem Troubleshooting – if you’ve had your no-name modem for several years already, you might want to call your internet service provider and have them troubleshoot it, and if necessary replace it. It would be a good idea to do your own packet loss test beforehand.

Additionally, some devices, the Amazon fire boxes especially, have a horrible time filtering the incoming wifi signal from radio frequency noise. TV's produce a huge amount of rf noise, right at 2.4 gHz, which is also the frequency that most wifi signals reside in. This can cause buffering, over heating, even hard reboots if it's really bad. You have two options to work around this: 1) Use a newer 5 gHz wifi channel if your router and box are capable. 2) Distance the box from the rf noise emanating from the TV. Simply moving a Fire TV Stick from being plugged into the back of a TV to sitting on a shelf a couple of inches in front of the TV can make a significant different. That few inches can mean the difference between Netflix content looking like newsprint at best or shutting down due to overheating at worst, and the picture coming in at full HD while the stick never gets beyond warm. Any HDMI extension cable should work fine, they can be found from amazon or monoprice for about $5.

 

## Can I use any repository to install an addon?

Do not use an unofficial repository or mass repository such as Super Repo.

Where possible use the original official repository.

Super Repo and many repositories like it are an unmaintained repository with many out of date, unmaintained and abandoned addons. Every legitimate/reputable guide will recommend using the official repository of an addon over any secondary repository (see seo-Michael, tv addons et al).

When a dev updates their addon, they upload the update to their own repository. This means that anyone who has that repository installed will instantly receive the update.

If you're using any other repository, you won't get the updated addon straight away. You will need to wait until someone manually adds the updated addon, the unofficial repository scrapes the updated addon or the update is uploaded​ in any other way so straight away, you're using obsolete versions of addons.

In addition to this, if someone creates a rogue fork of an addon and uploads it to an unofficial repository, you'll instantly receive this rogue update which could contain malicious code. You have no control over this or the effects it could have on your system.

Finally, quite recently, some unofficial repositories had an issue where they didn't have updated dependencies which meant that addon installations were failing. Users were left unable to install or update any addons.

There are many risks, many weak points and not much to gain from using these types of services.

## What does it mean when I keep getting the "Cache Full...cache filled before reaching required amount for continuous playback" error during playback?

The problem isn't that the cache is full, but that the video stream is too slow to playback without pausing again to wait for more of the video to download. It will still take just as long to load. Changing cache settings is not a magic wand. It helps only for people who have file transfers that are right on the edge or have fluctuating speeds. Generally speaking, modifying the advancedsettings.xml file will not solve buffering issues and will likely cause more trouble than anything, such as device crashing because the custom buffer size is larger than the device can handle (Kodi already allocates 300% of the memory to the buffer size). It is only useful only in the rare event that you see the “Cache Full: Cache filled before reaching required amount for continuous playback” notification.

## What do fully loaded boxes offer?

The people selling pre-configured kodi boxes do not offer anything whatsoever that can't be achieved with a combination of third-party addons and a customised skin for kodi. Kodi is free, open source software and the vast majority of third-party addons are also free of charge. The kodi community as a whole is strongly opposed to the selling of pre-configured boxes.

 

## How do I revert to a fresh version of Kodi?

There is two ways to do this, in Kodi using a plugin and also through the devices settings. This can be useful when encountering errors with Kodi or you want to install a new build. A relevant guide on how to fresh start your kodi using a plugin can be [found here](https://www.tvaddons.ag/factory-restore-kodi/). The second way to do this is via the device settings, I am an android user so other OS users please feel free to comment below if the method is not the same for other devices. Go to settings, then find applications, find Kodi and click clear data and clear cache. Now when you boot up Kodi you will find Kodi has gone back to default, with no add ons, vanilla Kodi.

 

## How can I watch live tv with third-party kodi addons?

There are a wide range of third-party kodi addons that serve up content from elsewhere on the internet, including from websites that host Live TV streams. Check out our monthly thread with third-party addons recommended by [/r/addons4kodi](https://www.reddit.com/r/addons4kodi) users and you will most likely find one for live tv. However, live tv streams are some of the most difficult to find and use with kodi so please bear this in mind. Whatever addon you choose, you will likely encounter many dead links and you will may have a frustrating experience.

 

## Will I encounter legal problems from using third-party addons with kodi?

It is unlikely but entirely possible you might encounter legal problems from using third-party addons with kodi. Many third-party addons serve up copyrighted content and the copyright holders are unlikely to want you to access their content for free. That said, online streaming is something of a grey-area in many jurisdictions and it is still highly unlikely you will face legal difficulties as a result of streaming copyrighted content using third-party addons with kodi. However, a small number of addons rely on P2P streaming and as a result you will also be uploading content as well as downloading content, meaning you are more likely to face legal difficulties. Using a VPN with kodi will help you avoid these legal problems.

 

## What are the best addons to install?

There is a sticky thread updated monthly which specifically answers this question.

 

## What are the benefits of using Trakt?

Benefits of Trakt have been covered in these Reddit posts and on Google:

- https://www.reddit.com/r/Addons4Kodi/comments/40dnhp/what_is_the_big_deal_with_trakt_for_salts/

- https://www.reddit.com/r/Addons4Kodi/comments/3z2xvs/benefits_of_linking_salts_with_trakt/

- https://www.reddit.com/r/Addons4Kodi/comments/3wpmvu/trakttv_why_use_it/

The Trakt Addon itself is only to keep your Kodi library and the Trakt database synced. You need to authorise Trakt into the addons you use to watch content in order for your Trakt information to be synced.

 

## What is the best build for kodi?

The best build is the one you create yourself. The pre-configured builds available from sources such as the Ares Wizard are nothing more than a selection of addons and a custom skin. [/r/addons4kodi](https://www.reddit.com/r/addons4kodi) doesn't recommend any pre-configured build but acknowledges they may be useful for new users to familiarise themselves with what can be achieved through with a combination of third-party addons and a customised skin. We advise users to install their own selection of third-party addons and to customise the look and feel of kodi with a skin of their own choosing.

 

## How do I install third party addons?

A quick google search with the name of the addon will likely yield a variety of step-by-step guides for installing the exact addon you are looking for, complete with pictures to make sure you don't go wrong. Most popular addons come from a small pool of sources so you'll find that once you've installed your first third-party addon, you will breeze through it the next time.

 

## Where does all the content come from?

The overwhelming majority of content served up to you by third-party kodi addons can be found elsewhere on the internet. Popular addons such as Icefilms and 1channel simply scour a specific website for the content you are looking for and serve it up to you from that website. Other addons, such as the popular SALTS addon, scour a wide range of websites to find the content you are looking for. Kodi does not host any content of its own and neither do the third-party addons. Think of third party add-ons as an automated Google search with a pretty results screen. The add-on developer has to program which online sources to search. The add-ons search these sources and produce the results without having to see the ads on those sites;

 

## How can I watch sports with third-party kodi addons?

There are a wide range of third-party kodi addons that serve up content from elsewhere on the internet, including from websites that host sports streams. Check out our monthly thread with addons recommended by [/r/addons4kodi](https://www.reddit.com/r/addons4kodi) users and you will most likely find one for sports.

 

## Are there any paid addons?

There are a wide range of services that offer kodi addons as a portal to access content from paid streaming services, including live tv and live sports. These addons are usually free to download and install although they will likely be useless without an account to access the paid streaming services. However, [/r/addons4kodi](https://www.reddit.com/r/addons4kodi) do not have any recommendations for paid kodi addons, although you may find recommendations from our users in the monthly addon recommendations thread.

 

## If all this content is available free of charge, what is in it for the third-party addon developers?

The overwhelming majority of third-party addon developers are kodi enthusiasts who, in most cases, have simply written the addons for personal use and decided to share their work with others. There is no financial reward for them to do so and you will not be expected to pay to use them. However, most third-party addon developers welcome donations to help pay for server costs and other expenses so feel free to help out if you would like to do so. Please remember the developers have been kind enough to share their work with the rest of us if you encounter problems with any of the third-party addons you might use.

 

## I have encountered technical problems with a third-party addon. What should I do?

Your first port of call should always be a quick google search to find out if there is a simple solution to your problem. If you are not having any luck with google, you can post on [/r/addons4kodi](https://www.reddit.com/r/addons4kodi) and if someone can help, we will. If you do post, please make your description as clear as possible and do not choose a title that gives little indication as to the nature of your problem. We are a friendly bunch on [/r/addons4kodi](https://www.reddit.com/r/addons4kodi) but we do encounter a large number of posts with little to no effort and no real description of the problem. Don't be one of those people. If you find a solution to your problem, please edit your post to include the solution so others might benefit.

 

## Why do I only see videos from the year 1970 and earlier (or year X and earlier)?

This is usually caused by your Kodi device having an incorrect Date/Time. Some third-party addons rely on the date and time of the device to scrape content. When your device is set to 2013 for example, these addons will only show content up to the year 2013 (no content from 2014 onwards). You'll need to access the date/time settings on your device and ensure that the correct date and time have been entered. Once the correct date and time have been entered, the addons should list content up to the current year.

 

## How do I fix this “No stream available” error? or Why does a Kodi add-on list a specific movie or TV show when there isn't a stream available?

99% of the time, a “no stream available” error in Kodi has nothing to do with any Kodi add-on. There is a misconception that Kodi add-ons are some magical treasure box of information that store information and links to every single movie and TV show on the internet. Multi-source Kodi add-ons like Exodus are simply glorified search engines. The list of movies and TV shows they offer are provided from the API key of a service like Trakt, IMDB or themoviedb. The list of links to each show are scraped from all of the sources loaded into the add-on. They store no streams and do nothing to update the list of shows or movies. Again, the list of movies and TV shows is just grabbed from another source like Trakt or themoviedb and presented in the add-on. If those services list a movie that comes out in theatres two weeks from now, this says nothing about whether a stream is available. Before using Kodi, perhaps you can try to go to the Primewire website, one of the largest databases for streams available, and search for your show or movie. If you don’t get any search results, you might have a hard time in Kodi as well. There is no “fix” for no stream available except to be smarter and more aware about what you are actually searching for. If you are absolutely certain that the stream you want is common and that there should be plenty of links (you are watching a popular show like The Walking Dead for example), reinstall Kodi from fresh with no add-ons. Nowadays, there are so many Kodi boxes, builds, and add-ons that its impossible to troubleshoot what the issue is exactly. If you want access to more obscure audio and videos, consider a premium Usenet provider alongside your Kodi system. The number of files available to stream here is magnitudes greater than anything in Exodus or other add-ons. These may be the only way to get the stream you want.

 

## Every time I select a certain provider, it only shows the 'working' dialogue, it does nothing, shows an error or all I see is pigeons, Rick Roles, the wrong content or a warning that I'm not accessing the content as it was intended. What's going on?

Users need to understand that Kodi addon developers and Streamers are two different groups. In fact they are two groups against each other. Streamers provide pirated content for profit. They get their profit by ads on their websites. Addon developers provide a way to show their streams on Kodi with no ads. This takes away from their profit. It's an endless game of cat and mouse. Streamers constantly change how they technically provide their streams and Addon developers constantly upgrade their addons to reflect those changes and be able to connect to those streams. This applies to movies/tv, live tv, and sport streams. This means that a certain provider may work perfectly today but not at all tomorrow. Similarly, a provider that didn't work yesterday may work extremely well today. This is completely dependent on the addon developer overcoming the change that the streamer has implemented. As a user, all you can do is be patient and appreciate that someone is there to fix the issue.

Users also need to understand that these addons don't label the media. They only display the information they are given. If an episode is mislabeled in these addons, it's because it's mislabeled by the provider. There are a few reasons this could occur:

- the uploader made a genuine mistake labelling the content;
- the uploader is a troll and intentionally mislabelled the content;
- common words in the content title may mislead the scraper to selecting the wrong content;
- there was a special/double episode which disrupts the episode count;
- there was a change in episode order between airing/DVD release and the provider is using the "wrong" one.

In the end though, none of these are in your control.

 

## Why is it so difficult to find a quality live stream through Kodi addons?

Live streaming is unreliable because of its very nature. With on-demand streaming, people watch the same stream at different times so the servers don't get massively overloaded (as often) and start buffering. With live sports being live, everyone is on at the same time and the servers get hammered. One solution is to use p2p streaming which, in theory at least, means the more people watching the stream at the same time the more people there are for you to leech from. Acestream is probably the best p2p live sports streaming option out there at the minute and it works fairly well with kodi, if you don't mind tinkering about a bit. A VPN is a good idea with p2p streaming because your ip address is visible to everyone connected to the stream, including copyright people who might want to catch you out for watching illegally. A VPN will keep you safer if you're using p2p streams but it probably won't do much to make ordinary http streams work better.

One probable reason is that most people who host the http streams are relying on advertising revenue to make money. If you're watching their streams through kodi, you're not viewing their advertisements and they're not getting paid. Websites probably make changes to their websites to keep kodi users out. This means developers have to work really hard to make sure the links on the various websites still work. It's probably a lot of effort and the add-on developers aren't getting paid so they might not always have the time to stay one step ahead.

Another possible cause has been reported by users who use specific ISPs that block content providing websites as their internet service provider. If you use BT in the UK for example, disable your “home hub smart setup” and see if this fixes your issue. This could also be a geolocation restriction placed on the content by the provider. This means that the content is only available to users from a certain country. To circumvent this, you can sign up for a VPN service like IPVanish or PIA and make yourself appear as if you are from a different location and ISP.

 

## How do I access the Kodi log to get assistance with an error?

If only there were a [website you could search](https://www.google.com.au/search?q=kodi+log+file) that could tell you how to check the log.

You should probably also share the log with us so we can figure out what's going wrong and help you. [Here is a guide](http://kodi.wiki/view/Log_file/Easy) to accomplish this.

The log file is located in the following locations based on your operating system:

- Windows: C:\Users{user_name}\AppData\Roaming\Kodi\kodi.log
- Android:{storage}/Android/data/org.xbmc.kodi/files/.kodi/temp/kodi.log
- Linux: ~/.kodi/kodi.log
- iOS: /private/var/mobile/Library/Preferences/Kodi/kodi.log
- Mac: /Users/{user_name}/Library/Application Support/Kodi/kodi.log
- OpenELEC: /storage/.kodi/kodi.log
- OSMC: /home/osmc/.kodi/temp/kodi.log
- XBian: /home/xbian/.kodi/temp/kodi.log
 

## What is this annoying bubble/icon/circle/image on the right of my Android device?

This actually has nothing to do with Kodi. You have ES File Explorer installed on your device. You'll need to modify the settings in ES File Explorer or uninstall the app completely to remove the icon from your screen.

 

## When I try to play content I receive a notification to go to a website and pair my device. What is this?

Some file hosts used by Kodi addons are tired of consistently trying to block access from Kodi so as a compromise, they have implemented a security feature requiring users to visit the host site in order to "pair" their device with the site database.

### Why is this happening?

File host sites receive revenue through ads on their website. By using Kodi addons to access the content, users are circumventing these ads and subsequently, these sites are losing revenue. To mitigate this, the host sites have implemented a security feature requiring users to access the site in order to "pair" their device with the site database.

### Is this safe?

Whilst potentially annoying, this process should be safe however as with anything illegal(grey area) online such as piracy, you use this at your own risk and should implement any sort of security measures you feel necessary.

### Do I have to do this?

If you would like to use these file hosts, yes however there are many file host sites available through Kodi addons, many of which do not implement these security measures.

### How often will I have to do this?

Depending on the file host, some of these pairing sessions may last for a single content playback, some may last for a period of time and some may last until your IP changes. This is completely dependent on the file host site.

### How does this work if I'm using a VPN on my device?

If all devices on your network are running through the same VPN (vpn implemented through the router), this will work fine. If however the VPN is only implemented on a single device, you may not be able to pair with these host sites and therefore may not be able to access the content from that source.

### My device does not have a web browser, how can I pair my device?

You don't have to use the same device to pair with the file host although this is generally the easiest method. If you're using a device that cannot access the website, you can use any device on the same network (shares the same external IP address). This means that if your device is using wifi, any device on that same wifi network can be used to pair with the file host site.

### How can I turn these file hosts off?

You may be able to disable these providers in specific addon settings by disengaging the "Hosts with captures" setting or removing them from the addon provider settings. You may also be able to disable them through the URL resolver addon.

## Why do I keep getting an error "Cache Full...cache filled before reaching required amount for continuous playback"

The video cache is the most common cache that people talk about when it comes to Kodi. The video cache works by saving a few seconds of video before it is needed, so that if there are small slowdowns or bumps in loading the video, it will not constantly pause while waiting to get enough data to resume playing back. The video cache is normally stored in RAM and erased on the fly, as needed. It requires no user intervention to "empty" this cache.

A warning about the cache filling up does not actually mean that more cache space is needed or that the existing cache needs to be emptied. The warning box is not currently well worded and has lead to a lot of confusion with users. What it means is that the video is loading too slowly for the cache to smooth out all of the bumps, and that the bumps will keep happening due to that low video speed.

Kodi only uses a tiny amount of RAM for the video cache, about 60 MB. This is because Kodi is not currently coded to see if the hardware you are using has more or less RAM, so to be safe only a small amount is assumed to be available. Users are able to increase this amount, and modify how "quickly" it fills up however, changes to these settings are only helpful for a few situations, such as a network that fluctuates in speed, occasional wifi interference, or a connection that is borderline too slow for video to playback.

Note: No amount of video cache tweaking will make a slow server connection any faster, which is a common issue for people who stream over the internet. Even if you have a fast connection on your device, it doesn't matter if the connection on the other end is slow. The server itself might not always be slow, but might be more busy at different times of the day.

## What is Real Debrid?

Real Debrid is a link premium access unlocker. Have you ever been to a file host site and they offered you a paid fast premium download or a slow download for free. Real Debrid let's you access the premium download without paying that file hoster - you pay Real Debrid and they pay the file hoster and share this among their subscribers
