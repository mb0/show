Show
====

This project is dead for now. You can read my last recording [log entry](./REC.md) if you are
interested in the details.

I wanted to record me playing my conga to good songs and share the result. It sadly only works as
long as you don't try to ask for permission, as is evident by lots of content on youtube.

The show should only use open source software. There is not much free hardware yet.
Free music should be featured, but a shallow search revealed not much progress there.

Hard and software
-----------------

My father is well known for his [bricolages](https://en.wikipedia.org/wiki/Bricolage), I learned
from him to use and repurpose the things directly available. My setup is based on that spirit:

 * General
   * [Debian Linux testing](https://www.debian.org/) on a custom PC
   * Schalloch Percussion Conga, from a friends fathers estate
 * Audio
   * Shure SM57 microphone with tripod 125€
   * Superlux E303 boundary microphone 45€
   * M-Audio M-Track Duo audio interface 55€
   * [Ardour 7](http://ardour.org/) digital audio software using [PipeWire](https://pipewire.org/)
   * [Calf Studio Gear](https://calf-studio-gear.org/) audio plugins
   * Superlux HD 681B headphones for playback, that I already had
 * Video
   * Samsung Galaxy S9, a gift from my brother
   * An old photo tripod from my father, with a new smart phone adapter
   * A larger micro SD card 12,99€ and a tripod adapter for phones 9,99€
   * [srccpy](https://blog.rom1v.com/2018/03/introducing-scrcpy/) to remote control recording
   * [Blender](https://www.blender.org/) as video editor
   * I bought a directors clap in hope to someday use it for automate visual clap detection 20,99€
 * Lighting
   * LED wellness daylight lamp; a gift from my best friend for dark northern winters
   * A white 23" PC monitor as fill-light
   * LED room lights as back-light
   * Space blanket to tint and reflect the key-light 1,30€
 * Publishing
   * I want to subscribe to soundcloud next plus, but that would be 5.50€ a month, so maybe I should
     wait and see if anyone is interested in chipping in.
   * TODO: Custom webapp that serves content and manages copyright permissions from rights holders

Without counting my PC and the headphones, the combined costs are 270,27€.

I eventually want to share the raw recordings and Ardour project with git to allow others to easier
use and collaborate the recordings. For that to work with long recordings we should use FLAC sources
and git large file storage for long mixes to not trigger file size limits on github.

The video editing part is not really feasible to share on github. For one the editor is linux only
and the file sizes involved are way to big for public hosting. We can save it to a private web
library and give out explicit access to authenticated users.

We should add document linking to generic setup and detailing the required extras. We can hide
copyrighted music from version control and provide a link and script to download, convert and save
the audio files for the playback track.

Music
-----

I want to upload recordings to soundcloud and youtube, therefor songs must either be in the public
domain, have a creative commons cc-by or cc-by-sa license, or I must collect the explicit
confirmation of all relevant rights holders.

[The recording diary](./REC.md) logs the order and songs that were recorded with some notes.

I decided to upload videos to [my youtube channel](https://www.youtube.com/@mbnull) and see what
happens. I want to at least try the default way using youtube detection and fair-use disputes.

### Public domain

To my shock music from 1920ies is not well recorded. Some public domain music can be found at:

 * [Library of Congress](https://loc.gov/)
 * [Project Gutenberg](https://www.gutenberg.org/)
 * [Open Music Archive](http://openmusicarchive.org/)

### Creative Commons

 * [Free Music Archive](https://freemusicarchive.org/) has few nice songs, but they are far between.
 * [Soundcloud](https://soundcloud.com/) has more well mixed cc-by and cc-by-sa songs by artists and
   is probably a better place to search for and share free music.

### Copyrighted

Most songs I want to play along to are under active copyright and need explicit permissions.

To make collecting permissions a happy and cheerful experience for copyright holders I want to give
them private pre-release access to their remixed work with a email, a link and a token. The idea is
to use either include the soundcloud widget and sync it up to to a embedded video or use a custom
widget to fade between original work, mix and solo conga. I want to be explicit about how to present
the derivative work, and provide three two for the rights-holder to choose from:

 * only used in a mix
 * allow using in a fader widget

When signed in a rights holder should be shown a header that informs him about pre-release
visibility and a call to action. Every rights holder should see the whole public listings as well as
an easy accessible listing to pre-release songs that need their approval.

I should record a short video intro to explain my mission to ease on-boarding for visitors.

The page could handle and automate uploads, conversions and publishing to multiple platforms.

Licenses
--------

 * Software written for this project should be published under a permissive BSD 2-Clause license.
 * The logo, web-design and text content should be licensed as cc-by-nc-sa.
 * The recordings vary from public domain, cc and special licenses.

