# password_cracking_rule

This is a supporting repo for blog post https://www.notsosecure.com/one-rule-to-rule-them-all/


“Our super rule came out on top in all our tests, as well as others we looked at after. We’re sorry to disappoint any Lord of the Rings fans (“One ring to rule them all!”), but despite our rule name, there likely won’t ever be one rule to rule them all as other rule based attacks wouldn’t exist if there was. Password attacks should always be executed factoring in all variables, in particular the available time, hardware resources, dictionary size and algorithm.”

# Credit where credit is due
The rule file is a combination of rules from various sources

1. https://github.com/praetorian-inc/Hob0Rules (d3adhob0.rule, hob064.rule)
2. http://contest-2010.korelogic.com/rules-hashcat.html (KoreLogicRulesPrependRockYou50000)
3. https://github.com/NSAKEY/nsa-rules (_NSAKEY.v2.dive.rule)
4. https://github.com/hashcat/hashcat/ oclHashcat v1.20 (by https://github.com/evilmog) (generated2.rule)

If we have missed adding someone in credit, feel free to send a note or open a github issue and we will sort it out.

# License
Rules taken from other ruleset will follow respective license.
Additional custom rules are added besides those mentioned above, these additional rules are MIT Licensed.
