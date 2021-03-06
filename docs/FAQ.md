# Frequently Asked Questions / Foire Aux Questions

## General / non-technical questions

### What is Whyd / Openwhyd, what does this name mean?

If you're curious, read [our story](https://medium.com/openwhyd/music-amongst-other-topics-a4f41657d6d).

### 🇬🇧 How to add music tracks?

Openwhyd offers several ways to add a music track:

1. click on the "Add" link of a track added by someone else, e.g. from [the stream](https://openwhyd.org/stream) (followed users), or from the [hot tracks ranking](https://openwhyd.org/hot);
2. type the title of the track or paste its YouTube URL in Openwhyd's search bar;
3. or use the [Openwhyd➕ button](https://openwhyd.org/button) from a web page that contains a track (after installing our extension for Google Chrome, or bookmarklet).

Demo: https://www.youtube.com/watch?v=aZT8VlTV1YY

### 🇫🇷 Comment ajouter de la musique ?

Pour ajouter un morceau de musique (appelé *track*), Openwhyd propose plusieurs moyens:

1. cliquer sur le lien "Add" d'un morceau ajouté par quelqu'un d'autre, ex: depuis [le stream](https://openwhyd.org/stream) (utilisateurs suivis), ou depuis les [hot tracks](https://openwhyd.org/hot);
2. taper le nom du morceau ou coller l'URL YouTube de ce morceau depuis la barre de recherche d'Openwhyd;
3. ou utiliser le [bouton Openwhyd](https://openwhyd.org/button) depuis une page web contenant un morceau (après avoir installé l'extension pour Google Chrome ou le bookmarklet).

Démo: https://www.youtube.com/watch?v=aZT8VlTV1YY

### How to use Openwhyd on my mobile phone?

So far, Openwhyd can be used from the following devices only:

- use the [web version](https://openwhyd.org) on your computer.
- use our [iOS app](https://openwhyd.org) on your iPhone or iPad.
- if you have another kind of smartphone or tablet, you can only use our experimental [Mobile Track Finder](https://openwhyd.org/mobile/) in order to search and play individual tracks from your Openwhyd profile.

Many users are hoping for an Android app. We'd love to make it, but it would take us a whole lot of time. So far, nobody from our community of users volunteered for this, unfortunately.

If you think that you can help in any way, please contact us!

### How many users are using Openwhyd? (among other stats)

You can find an infographic with a few facts and numbers [there](https://www.facebook.com/openwhyd/photos/a.1159960527358541.1073741828.1156477841040143/1218644401490153/?type=3).

### I'd love to contribute to Openwhyd, how can I help?

Openwhyd is a collaborative project, so we welcome contributions of any kind!

If you're a developer, check out:

- our [open-source repositories on Github](https://github.com/openwhyd),
- our [global roadmap](https://github.com/orgs/openwhyd/projects/1) and [development board on Github](https://github.com/openwhyd/openwhyd/projects/1),
- our [current issues on Github](https://github.com/openwhyd/openwhyd/issues), (*help on fixing bugs is particularly appreciated!*)
- and our [contribution guide](https://github.com/openwhyd/openwhyd/blob/master/CONTRIBUTING.md).

If you have other skills that you would like to invest as a volunteer, please contact us!

Or, if you want to keep Openwhyd afloat, you can [donate](https://opencollective.com/openwhyd) to help us cover Openwhyd's hosting costs.

### How to contact Openwhyd's team?

Contact us at contact@openwhyd.org, or through our [Openwhyd Music Lovers Club, on Facebook](https://www.facebook.com/groups/openwhyd/). Our community of volunteers and users will do their best to help!
 
## Technical questions / support

### Track skipping problem / les morceaux sautent / ne s'enchainent pas ?

Try to refresh the page and click again on the track to see if it plays.
  - If it does not, try opening its source URL to another tab by right-clicking on it, and play it from there.
    - If it does not play from its original location (e.g. Youtube page), there is nothing we can do, unfortunately...
    - If it does play from there but not from Openwhyd, it could be caused by geographical limitations (i.e. for technical reasons, the track must be allowed to be streamed in France), or that our player is broken. => Please let us know by sending us the Openwhyd URL of your track.
  - If it does play after refreshing the Openwhyd page, it could be that your web browser does not allow playback of streaming content in the background (i.e. while doing something else.) In that case, try installing [Openwhyd-electron](https://github.com/openwhyd/openwhyd-electron/releases/) on your computer, by selecting your operating system from the list.

### I can't add / bookmark a track from Youtube ...

![screenshot](https://scontent-cdg2-1.xx.fbcdn.net/v/t31.0-0/p180x540/19243083_10213413094510997_2243898622608810090_o.jpg?oh=ec7af0fc25de2e7fc692d7ac575afb49&oe=59CCB0FB)

Solutions:

1. Try uninstalling and re-installing the extension;
2. Empty your browser's cache;
3. Or uninstall and reinstall your web browser.

It could also be that this track is not accessible from France, as explained in the answer above.

### How to export my tracks / comment exporter ma musique en CSV ou JSON ?

🇬🇧 First off, don't worry! Like you, we really care about our 5+ years of music curated with love on Openwhyd! And, whatever happens, we would never let Openwhyd *die* without warning the community beforehand.

That being said, it's very easy to download your data at any time: just add the `?format=json&limit=999999` suffix to your Openwhyd profile URL. E.g. `https://openwhyd.org/adrien?format=json&limit=999999`

*More info: read [how to download Openwhyd track listings in JSON format](howto-backup-openwhyd-tracks.md).*

🇫🇷 Tu peux récupérer tes tracks à tout moment, en ajoutant le suffixe `?format=json&limit=999999` à l'URL de ton profil Openwhyd. Exemple: `https://openwhyd.org/adrien?format=json&limit=999999`

### Do you have an API ?

Yes, check [this](https://github.com/openwhyd/openwhyd/blob/master/docs/whydJS-json-api.md) out.

### The player says “Embed too small” or something like that, and wont play my music! 
 
Yeah, this happens, the embed is about as small as it can be without breaking the rules, but that sometimes means that when people have a zoom on their browser that the window is too small to play the media. Check the “View” tab and set it to 100%, that should fix the problem in most cases. 
 
### Sometimes a track doesn’t play at all, or it says that I have to go to YouTube to view the content.
 
Well, it’s true, there is some music that cannot be embedded onto other sites without explicit permission from the rights holders. If we don’t have an agreement in place you have to go to YouTube to watch it. But don’t worry, we are working on a bunch of solutions to that very problem! 
 
Other times the player is trying to activate the media but the connection slows down for whatever reason and the play action times out. In this case the player skips to the next song. Try clicking on the song that was skipped, most of the time it will start playing. This problem comes from the fact that with continuous playback there are certain conditions that must be set to make sure that your music doesn’t get stuck on a track that’s acting a little unruly. 
 
But overall keep in mind that we support music from a lot of different sources, and these sources are continuously evolving and changing, so we strive to make 99% of tracks work, and we are definitely hitting our goal!
 
### When I click on a track it takes me to the Soundcloud page! 
 
That happens too, try refreshing the Openwhyd page. 
 
### The video plays on top of the notifications panel!
 
Yeah, that’s because of Flash. Please try again after activating the HTML5 mode of Youtube (http://youtube.com/html5), and contact us if you still experience this issue.
 
### Other: I have a problem that you didn’t mention here, what should I do about it?
 
Contact us at contact@openwhyd.org, or through our [Openwhyd Music Lovers Club, on Facebook](https://www.facebook.com/groups/openwhyd/). Our community of volunteers and users will do their best to help!
 
*Never stop jamming!*
