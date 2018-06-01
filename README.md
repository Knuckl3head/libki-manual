# Introduction

![Libki Kiosk Management System](.gitbook/assets/libki-banner.png)

## Libki Basics

Libki is a Free Open Source cross-platform pc reservation booking and time management system designed to allow time limited access to computers on a network. Libki is ideally suited for use in locations where a controlled computing environment is paramount such as public access systems, libraries, school computer laboratories and more! It consists of two parts, the Libki server, and the Libki client.

Learn more about Libki by visiting the official Libki website: [http://libki.org](http://libki.org)

### The Libki server

The Libki server utilizes a web-based administration system that can be accessed from any networked pc via a web browser. From the web administration one can create and delete users, change the amount of time left on an account, send or leave a message for a user, log out and/or ban users, and see which client computers are available and which are currently being used. In addition, the system has a public web interface for viewing which kiosks are available, which are unavailable, and to allow the placing of reservations.

### The Libki client

The Libki client is cross-platform and runs on many operating systems including Microsoft Windows and Linux. The Libki client features a counter to let the user know how many minutes are left, and the ability to log off early. Any unused minutes can be used at any other computer running the Libki client. The Libki client can be set to log off from the operating system, or even reboot the computer when a user logs off from the Libki client.

## Libki Server recommendations

At the time of this writing, it is recommended to run Libki Server on [Debian Linux](https://www.debian.org/), or via [Docker](https://www.docker.com/).

Guides for both deployment types are available in the [Installation](installation.md) section.

Libki Server is meant to work on all web browsers, but is most tested on Chrome and Firefox.

### Using this Manual

This manual is always changing and suggestions for edits can be sent to the Koha Documentation Team as a merge request via gitlab or via the [koha-docs mailing list](https://lists.koha-community.org/cgi-bin/mailman/listinfo/koha-docs). The manual is organized by Koha module. At the start of most sections \(and throughout\) you will find ‘Get there’ tips. These lines tell you how to get to the section in Koha.

For example: _Get there:_ More &gt; Administration &gt; Global system preferences

Get there: More &gt; Administration &gt; Global system preferences

The instruction tells you where to find the necessary menu option at the top of the Koha staff client.

Links will be found throughout the manual to other sections in the manual and images will depict what should be seen on the screen.

### Contributing to the Manual

This manual is an ever-changing document and edits to the manual are welcome at any time.

The [Koha Manual](http://manual.koha-community.org/) is managed by the Documentation Manager, but that doesn’t mean we can’t all participate in making the best manual possible.

The manual is stored in git at: [http://git.koha-community.org/gitweb/?p=kohadocs.git;a=summary](http://git.koha-community.org/gitweb/?p=kohadocs.git;a=summary)

