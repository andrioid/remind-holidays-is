remind-holidays-is
==================

Icelandic Holiday Definitions for Remind (http://www.roaringpenguin.com/products/remind)

## Why?

I got frustrated using 3rd party versions of the Icelandic holidays for my calendar. Most of them have errors, many have become outdated and all depend on someone else to update this every year.

Remind is an extremely powerful calendar software and I utilize that to create an up-to-date holiday list.

## Compile to iCal

1. Fetch [rem2ics](http://www.roaringpenguin.com/wiki/index.php/Rem2ics)
2. Run: "remind -s ~/is.rem | TZ=GMT0 HOSTNAME=tiny.scrolls.org ./rem2ics -do >  holiday.ics"
3. Enjoy your updated holiday file.

## That's nice, but I really just want to import the iCal file

I will make that available soon - I promise.
