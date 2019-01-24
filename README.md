# OneRuleToRuleThemAll

This is a custom hashcat rule, the original supporting blog post of which I wrote when I worked at https://www.notsosecure.com 

Several default and non-default hashcat rules were individually tested over a set of 4.3 million unique MD5 hashes from a data breach.
Hashcat debugging provided statistical analysis of the best performing and most efficient rules in each test.
The best performing 25% of rules from each tested ruleset were extracted and concatenated into a new custom rule.

OneRuleToRuleThemAll cracked 68.36% of the 4.3 million hashes; an increase of 2.72% (117,626 hashes) over second place which was the hashcat supplied dive rule.


# Credit
Aside from hashcat supplied rule sets, shout outs to the following rule sets that were used for testing:

1. https://github.com/praetorian-inc/Hob0Rules (d3adhob0.rule, hob064.rule)
2. http://contest-2010.korelogic.com/rules-hashcat.html (KoreLogicRulesPrependRockYou50000)
3. https://github.com/NSAKEY/nsa-rules (_NSAKEY.v2.dive.rule)
4. https://github.com/hashcat/hashcat/ oclHashcat v1.20 (by https://github.com/evilmog) (generated2.rule)

Please get in touch if anyone has been missed.

# License
Rules taken from other ruleset will follow respective licenses.
Additional custom rules are added besides those mentioned above, these additional rules are MIT Licensed.
