# grocy
ERP beyond your fridge

## Motivation
A household needs to be managed. I did this so far (almost 10 years) with my first self written software (a C# windows forms application) and with a bunch of Excel sheets. The software is a pain to use and Excel is Excel. So I searched for and tried different things for a (very) long time, nothing 100 % fitted, so this is my aim for a "complete houshold management"-thing.

## What it is about
For now my main focus is on stock management, ERP your fridge!

# Give it a try
Public demo of the latest version &rarr; [https://grocy.projectdemos.berrnd.org](https://grocy.projectdemos.berrnd.org) 

## How to install
Just unpack the [latest release](https://github.com/berrnd/grocy/releases/latest) on your PHP enabled webserver, copy `config-dist.php` to `data/config.php`, edit it to your needs, ensure that the `data` directory is writable and you're ready to go. Alternatively clone this repository and install Composer and Bower dependencies manually.

## Notes about barcode readers
Some fields also allow to select a value by scanning a barcode. It works best when your barcode reader prefixes every barcode with a letter this is normally not part of a item name (I use a `$`) and sends a `TAB` after a scan.

## License
The MIT License (MIT)
