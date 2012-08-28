jquery.printarea.js
===================

A clone of SkiKid's jQuery print plugin to fix compat issues with jQuery versions above 1.6.x

Added fix for the "media is undefined" error that affected code using jQuery version > 1.6.x. The problem was that jQuery returns undefined for non-existent attributes above 1.6.x. Added a typeof check for undefined media attribute.

This repo was made to host an updated version of SkiKid's (http://archive.plugins.jquery.com/users/skikid) print assist plugin that is currently unavailable due to jQuery plugin repo outage.