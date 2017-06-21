# vowel-sanctuary

The owls will tell you a unique password that looks like it is
made of upper case vowels
_but which is actually made of Greek, Coptic, and Cyrillic Unicode!_

<img src="https://raw.githubusercontent.com/edwardspeyer/vowel-sanctuary/master/images/screenshot.png" width="450">

The _vowels_ correspond to sets of Unicode homoglyphs:
letters that look the same.
None of them are from the actual ASCII set,
but they should look idential to their ASCII equivalent.

If you are using the right sort of typeface, an adversary who is
spying over your shoulder and sees a password starting with "E"
wouldn't be able to tell if it is an
E (_latin capital letter E_, which would never actually be chosen by vowel-sanctuary),
Ε	(_greek capital letter epsilon_), 
Е (_cyrillic capital letter IE_),
or
Е (_lisu letter E_).
Each vowel that is used comes
from a set of two or three choices spread over different Unicode
code pages.

The regular entropy of the password is printed (⚄), as well as the
entropy of the password if someone is spying over your shoulder (☭):
the adversary knows which sets of homoglyphs had been used in
each position, but _doesn't know_ the actual glyphs used.

# /COOPER/COOPER/COOPER/COOPER/

<a href="https://youtu.be/mbi7rq-TSk8?t=114"><img src="https://raw.githubusercontent.com/edwardspeyer/vowel-sanctuary/master/images/youtube.jpg" alt="THE OWLS ARE NOT WHAT THEY SEEM" width="640"></a>
