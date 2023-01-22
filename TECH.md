Tech
====

We want a stand alone program that manages and serves a media library either locally or through the
web.

Use-cases
---------

 * multi tenant media library
   * tenant, projects, themes, tags structure
   * versioning and metadata of files, copyrights tracking for derivative works
   * original files like audio or video recordings, or placeholder links for external data
   * derived files, like mixes or different output formats, that track sources and copyrights
   * private, draft, published status
   * draft sharable with other tenant or with link and token, time limited shares

 * rights management
   * manage and identify rights holders and their contact info
   * send email request link and token to permission interface

 * web site / blog
   * write and manage drafts with title, description, text body and media files
   * manage and replace links to published media files on public platforms like youtube, soundcloud

 * roles: admin, member, user, copyrighter, guest

Environment
-----------

The program should foremost be made to work in my computer systems that run Debian linux. Much later
we can think about other platforms.

I want to use this opportunity to use another project of mine. The program would be written in Go
programming language and use an Sqlite3 file or PostgreSQL backend.

We can use:
 * my [daql](https://xelf.org/daql) project for model schemas
 * [tusd](https://github.com/tus/tusd) for resumable uploads
 * [goldmark](https://github.com/yuin/goldmark) form markdown processing
 * exec [ffmpeg](https://ffmpeg.org/) commands for media conversion and simple workflows
 * [goth](https://github.com/markbates/goth) auth for github, youtube (google) and soundcloud users
 * maybe the soundcloud, youtube and github apis are easy enough to use for our workflows,
   otherwise there are libraries and utility programs to do the job
