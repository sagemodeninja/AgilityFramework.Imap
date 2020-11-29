### Introduction

This repository contains an easy-to-use and well-documented .NET assembly for communicating with and
receiving electronic mail from an Internet Message Access Protocol (IMAP) server.

**Note:** This is a direct port of [S22.Imap](https://github.com/smiley22/S22.Imap)
          into .NET Standard.

### Downloads

You can get the latest package on [Nuget](https://www.nuget.org/packages/AgilityFramework.Imap/).

### Usage & Examples

Read smiley22's repository [readme](https://github.com/smiley22/S22.Imap/blob/master/Readme.md) to learn more.

### Features

+ Supports IMAP IDLE notifications
+ Supports IMAP over SSL
+ API designed to be very easy to use
+ Allows selectively fetching parts of mail messages
+ Inherently thread-safe
+ Well documented with lots of example code
+ Robust MIME parser, tested with 100.000+ mails
+ Supports various authentication mechanisms (SCRAM-SHA-1, OAUTH2, NTLM among [others](https://github.com/sagemodeninja/AgilityFramework.Imap/blob/master/AuthMethod.cs))
+ Integrates well with existing System.Net.Mail infrastructure
+ Still supports .NET 3.5
+ Free to use in commercial and personal projects [MIT license](https://github.com/sagemodeninja/AgilityFramework.Imap/blob/master/License.md)

### Credits

Copyright © 2020 Gary Antier.

Original project [S22.Imap](https://github.com/smiley22/S22.Imap) copyright © 2012-2014 Torben Könke.

```RIPEMD160Managed``` are based on **[System.Security.Cryptography.RIPEMD160](https://github.com/darrenstarr/RIPEMD160.net)** project.

### License

This library is released under the [MIT license](https://github.com/sagemodeninja/AgilityFramework.Imap/blob/master/License.md).

### Bug reports

Please send your bug reports to [contact@garyantier.com](mailto:contact@garyantier.com).
