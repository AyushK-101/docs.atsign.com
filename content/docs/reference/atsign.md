---
layout: single

title: "atSign" # The title (ON THE PAGE)
lead: | # The lead below the title (ON THE PAGE)
  What an atSign is in the atPlatform

description:
  | # SEO Description of the page (Shows in google and atsign.dev search)
  Learn about what an atSign is in the atPlatform

draft: false # Change this to "true" to hide the page
toc: true # Change this to "true" to show the table of contents
weight: 200 # For single pages, lower is first.
---

## What is an atSign

An atSign is a handle (e.g. @alice) that functions as your digital identity. It uses end-to-end encryption to ensure that your data is 100% owned and controlled by you.

An atSign has two states: deactivated and activated. To activate an atSign, [CRAM](/reference/cram) authenticate into your [secondary server](/reference/synchronization/). After successful CRAM authentication, your atSign is activated where a [PKAM](/reference/pkam/) key pair is generated by your device and the CRAM key will be invalid; so that only you own the keys to your secondary server.

Each atSign has a unique key that is used to verify whether you are the atSign’s rightful owner. After first activating an atSign, be sure to save its corresponding key in a secure location. You’ll need it to sign back into the app or use other apps on the atPlatform.

## Example

Alice has created their own atSign called @alice. Anyone who looks up @alice can only view the information that they’ve made public through [@wavi](https://atsign.com/apps/wavi/), an app that lets them set up and customize their public profile. They’ll have the freedom to adjust it as needed, and those changes will be viewable in a matter of seconds.

## What you can do with an atSign

At the moment, you can pair your atSign with any app on the atPlatform (the underlying technology behind atSigns) to enable the app to access, but not store, your data. The number of things you can do with your atSign will increase as more and more of these atApps are built.

While we wait for the rest of the Internet to catch up, you can get ahead of the game by downloading the first batch of recently launched atApps. These include @atmospherePro, an end-to-end encrypted file sharing app, @buzz, an entirely new and private way to connect with others, and more.

Discover these atApps [here](https://atsign.com/apps/).
