Instagram Challenge
===================

StieglitzGram
-------------

I have named my instagram clone after Alfred Stieglitz who is regarded as being  responible for making photagraphy an accepted art form.
At the time photography was seen as hobbyists pastime for bicycle clubs to record their travels. Stieglitz was instramental in getting fine art institutions (most notably MOMA) to the show the work of photographers alongide painters and sculptors.  He was was also married to painter Georgia O'Keeffe

Installation
```sh
git clone the repo
```

I have git ignored the photos I used for testing. You need to add them to /spec/assets_specs/photos/ if you would like to test images. You will also need to ensure the file names match those in the test that use photos

user stories

```
As a candid phototographer
so I can show people my photos
I want to post my photos to StieglitzGram

As a candid photographer
So that I can post photos on StieglitzGram
I would like to join up to StieglitzGram

As a candid photographer
So that I can post photos as me
I want to log into StieglitzGram

As a candid photographer
So that I can avoid others posting as me
I want to log out of StieglitzGram

As a candid photographer
so I can tell other photographers what I think of photos
I would like to comment on any photo

As a candid photographer
so that I can indicate wether I like a photo
I would like to be able to add a like to any photo

As a curator of photography
so I can see which photos are popular
I would like to be able to see the count of likes per photo

As a curator of photography
so that the popularity is fair
only members of StieglitzGram are allowed to like photos

As a curator of photography
so that the popularity is fair
Each member should only be able to like a photo once

```
Lessons learnt

* factory girl set up with rails. Install factory girl at start of project and it will build the factory template files for you as you add
* git ignore the photos directy so they are not uploaded to git hub
* Phantom JS for javascript testing with capybara
* If using phantom js in a test it affects factory girl factories you are trying to use in the test. They will not be recognised


Instructions
-------
* Challenge time: Friday, the entire day + the weekend if you need it
* Feel free to use Google, your notes, books, etc., but work on your own
* You must submit a pull request to this repo with your challenge solution (or partial solution) by 9AM Monday morning.
* extending active record associations

Task
-----

Build Instagram: Simple huh!

As usual please start by

* Filling out your learning plan self review for the week: https://github.com/makersacademy/learning_plan (if you haven't already)
* Forking this repo. After cloning your fork and cd'ing into it, you'll need to [initialize a Rails app in the current directory](http://blog.jasonmeridth.com/posts/create-rails-application-in-current-directory/).

Your challenge is to build Instagram using Rails. You'll need **users** who can post **pictures**, write **comments** on pictures and **like** a picture. Style it like Instagram's website (or more awesome).

Bonus if you can add filters!
