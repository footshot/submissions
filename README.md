# footshot.net submissions

The Footshot Project welcomes your submissions! Follow the guidelines below 
for submitting new entries via git. If you are having trouble submitting, 
use the web form at http://footshot.net/submit

## Guidelines

Submissions to footshot.net should follow the following guidelines:

* One file per submission.
* Wrap lines at 80 characters.
* File names should be: all lowercase, begin with the **_techslug_**, and 
  use dashes for spaces.
  e.g. `python.md`, `ruby.md`, `ruby-1.md`, etc.
* Refrain from editing others' submissions, unless a minor correction is 
  needed, e.g. spelling.
* Please do not rename files. 

## Sample format:

```
Techslug: unix
Title: Unix shell
Author: Unknown
Published: September 18, 2015
Version: 1.0
Syntax: no-highlight
-------

% ls
foot.c foot.h foot.o toe.c toe.o
% rm * .o
rm: .o: No such file or directory
% ls
%

```

## Submitting

Entries are periodically vetted and slurped into the footshot.net database. Please allow a few days for your entry to appear.

Failure to follow the guinelines above may result in pull request being 
rejected.

## Submissions

### Attribute: Techslug (required)

Techslugs are a standardized set of names for technologies with which you can shoot yourself in the foot. Techslugs are also the primary taxonomy used to classify a submission. 

When submitting, please ensure the appropriate techslug is used. If the technology you are submitting is not on the list, submit it with the most succinct version of the technology name.

i.e. use "assembly" rather than "x86 assembly"; or "PHP" instead of "PHP 5.3"

When the joke relies on a specific version of the technology, or some other idea needs conveyed, please use tht title attribute (below).

### Attribute: Title (optional)

Specify a title for the submission. Overrides the default title (from the **_techslug_**)

### Attribute: Author (optional, preferred)

Specify the author of the submission. Preferred format:

Author: Guy Smiley <bigmouth@sesamest.ca>


### Attribute: Published (optional)

Date published. Format can vary, provided it can be read by PHP's strtotime():
http://php.net/manual/en/function.strtotime.php

### Attribute: Version (optional)

Increase version number if necessary. This doesn't do much any may be removed.

### Attribute: Syntax (optional)

Override the syntax highlighter assigned by the **_techslug_**. 
To disable highlighting entirely, specify `Syntax: plain`

### Syntax Highlighting

Supported programming languages will have syntax highlighing applied via [highlight.js](https://highlightjs.org/). Currently highlight.js supports 135 different languages. View a [list of all languages](https://github.com/isagalaev/highlight.js/tree/master/src/languages).

## Contact

Contact the Footshot Project lead by using the contact form at
http://footshot.net/contact/

If you are having trouble submitting, 
use the web form at http://footshot.net/submit

Thank you!!

http://footshot.net

## License

See LICENSE