# lipsum D8 module

A custom lorem ipsum generation module for Drupal 8.

This project follows a Drupal docs tutorial on D8 custom module development. For more information, see: [A practical guide to building basic Drupal 8 modules](https://www.drupal.org/docs/8/creating-custom-modules/a-practical-guide-to-building-basic-drupal-8-modules).

---

## Instructions

Lorem ipsum dolor sit amet... **Just kidding!**

Unpack in the *modules* folder (currently in the root of your Drupal 8
installation) and enable in `/admin/modules`.

Then, visit `/admin/config/development/loremipsum` and enter your own set of
phrases to build random-generated text (or go with the default Lorem ipsum).

Last, visit `www.example.com/loremipsum/generate/P/S` where:

- *P* is the number of *paragraphs*
- *S* is the maximum number of *sentences*

There is also a generator block in which you can choose how many paragraphs and
phrases and it'll do the rest.

If you need, there's also a specific *generate lorem ipsum* permission.

### Maintenance

Most bugs have been ironed out, holes covered, features added. But this module
is a work in progress. Please report bugs and suggestions, ok?
