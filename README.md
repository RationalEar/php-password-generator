php-password-generator
======================

Random Password Generator using PHP with full working example


Changelog v1.0:
- first version ;)

Bugs:
- If you set passwords longer than is range
of characters while having enabled unique_chars,
than it will do nothing good.

Issues:
- way to get unique characters in password
can be improved. It's not the best solution
I think and sometimes causing slower load of
script.

Usage:
- See example.php

Notes:
- I'm now about to find a nice way to ensure
that password contains at least one character
from each option enabled.
- Also need to find a way how to keep some
security of code in unique_chars vs limited
count of chars range.
- Using special chars is disabled for default
becausing some systems, apps and websites don't
allow using them and also ppl in different
countries may not know how to make some of
them...

Copyright 2007-2009, Daniel Tlach

Licensed under GNU GPL

changed by Michael Schramm


Updated 23 Feb 2014 by Michael M Chiwere michaelmartinc@gmail.com

@copyright	Copyright 2007-2009, Daniel Tlach
@link		http://www.danaketh.com
@version		1.0
@license		http://www.gnu.org/licenses/gpl.txt
/
