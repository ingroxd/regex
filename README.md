# regex

All the regex listed, are tested on

https://regex101.com/

using the sintax PCRE (PHP) which is fully compatible with grep sintax, escaping apart.

You can quickly achieve grep escaping with the following command:
sed -i -e 's/[(){}|?+]/\\&/g' -e 's|\/|/|g' list.txt

