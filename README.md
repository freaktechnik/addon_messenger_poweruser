# messenger poweruser

A simple firefox addons to be more efficient and avoid the mouse on messenger.

## Features :

* mouse not needeed anymore, keyboard shortcuts (vim oriented) allowed you to use messenger through keyboard only
* dark mode

## How to install

### easy way @todo

1. go to (https://addons.mozilla.org/fr/firefox/addon/messenger-poweruser/) [https://addons.mozilla.org/fr/firefox/addon/messenger-poweruser/]

2. click add to firefox

3. enjoy :)

### hard way

1. build zip

```
git clone https://github.com/aloisleclet/addon_messenger_poweruser
cd ./addon_messenger_poweruser
zip addon_messenger_poweruser * */*
```

2. go to firefox
```
about:debugging#/runtime/this-firefox
```

3. Click on 'Load Temporary addons'

4. select addon_messenger_poweruser.zip 

5. enjoy :)

## How to use

1. login on your messenger account on your browser

2. test keyboard (vim like) shortcuts

* i           ->  focus chat input 
* /           ->  focus search input
* Escape      ->  blur all
* j           ->  scroll bottom (when no input are focused)
* k           ->  scroll top (when no input are focused)
* Tab         ->  switch between chat area and contact area (when no input are focused)
* h or l      ->  switch between chat area and contact area (when no input are focused)
* o           ->  open information sidebar (when no input are focused)
* u           ->  send a like or primary emoji (when no input are focused)
* d           ->  switch dark mode on/off (when no input are focused)
* a           ->  open active contacts (when no input are focused)

#### dev with <3 by @aloisleclet 
