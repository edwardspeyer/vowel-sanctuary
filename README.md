# vowel-sanctuary

The owls will tell you a unique password that looks like it is
made of upper case vowels
_but which is actually made of Greek, Coptic, and Cyrillic Unicode!_

<img src="https://raw.githubusercontent.com/edwardspeyer/vowel-sanctuary/master/images/screenshot.png" width="450">

The _vowels_ are Unicode homoglyphs: letters that look the same.
None of them are from the actual ASCII set, but they look almost
idential.

If you are using the right sort of typeface, an adversary who is
spying over your shoulder wouldn't be able to tell, for example,
whether you were using A, Α, or А.  Each vowel that is used comes
from a set of two or three choices spread over different Unicode
code pages (character sets.)

The regular entropy of the password is printed, as well as the
visual entropy of the password.  This second value is the entropy
as if an adversary had seen the password and known which possible
homoglyphs could have been used in each position, but still
didn't know the actual glyphs used.

# /COOPER/COOPER/COOPER/COOPER/

<a href="https://youtu.be/mbi7rq-TSk8?t=114"><img src="https://raw.githubusercontent.com/edwardspeyer/vowel-sanctuary/master/images/youtube.jpg" alt="THE OWLS ARE NOT WHAT THEY SEEM" width="640"></a>
