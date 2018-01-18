# App's Security Comparison
Based on EFF's [Secure Messaging Scorecard](https://www.eff.org/node/82654)



|   | 	Encrypted in transit? | Encrypted so the provider can’t read it? | Can you verify contacts’ identities? | Are past comms secure if your keys are stolen? | Is the code open to independent review? | Is security design properly documented? | Has there been any recent code audit? |
|    :---:     |     :---:      |     :---:     |     :---:    |     :---:      |     :---:     |     :---:      |     :---:     |
| **Facebook Chat**  | YES | [YES (Not the default option)](https://www.engadget.com/2016/10/04/facebook-messenger-now-lets-you-toggle-end-to-end-encryption/) | [YES](https://fbnewsroomus.files.wordpress.com/2016/07/secret_conversations_whitepaper-1.pdf) | [YES](https://fbnewsroomus.files.wordpress.com/2016/07/secret_conversations_whitepaper-1.pdf) | [YES](https://github.com/facebookresearch/asynchronousratchetingtree) | [YES](https://fbnewsroomus.files.wordpress.com/2016/07/secret_conversations_whitepaper-1.pdf) | No records of new audit has been found |
| **LINE**  | [YES](https://linecorp.com/en/security/encryption_report)  | [YES (Only Text Messages and Audio Calls)](https://linecorp.com/en/security/encryption_report)  | [YES](https://help.line.me/line/?contentId=50000087)   | [YES](https://linecorp.com/en/security/encryption_report)  | NO| [YES](https://scdn.line-apps.com/stf/linecorp/en/csr/line-encryption-whitepaper-ver1.0.pdf)  | [YES](https://www.usenix.org/system/files/conference/foci17/foci17-paper-espinoza.pdf) |
| **RestroShare**  | YES | YES| YES| YES| YES| YES| [NO (Last Revision on 2016)](https://www.elttam.com.au/blog/a-review-of-the-eff-secure-messaging-scorecard-pt1/) |
| **Signal**  | YES | YES| YES| YES| YES| YES| YES |
| **Silent Phone**  | YES | YES| YES| YES| [YES](https://github.com/SilentCircle/silent-phone-android)| YES| No records of new audit has been found |
| **Snapchat**  | YES | NO| NO| NO| NO| NO| No records of new audit has been found |
| **StartMail**      | [YES](https://support.startmail.com/index.php?/Knowledgebase/Article/View/520/2/startmail-on-effs-secure-messaging-scorecard) | [NO](https://support.startmail.com/index.php?/Knowledgebase/Article/View/520/2/startmail-on-effs-secure-messaging-scorecard) | [YES](https://support.startmail.com/index.php?/Knowledgebase/Article/View/520/2/startmail-on-effs-secure-messaging-scorecard) | [NO](https://support.startmail.com/index.php?/Knowledgebase/Article/View/520/2/startmail-on-effs-secure-messaging-scorecard) | [NO](https://support.startmail.com/index.php?/Knowledgebase/Article/View/520/2/startmail-on-effs-secure-messaging-scorecard) | [YES](https://support.startmail.com/index.php?/Knowledgebase/Article/View/520/2/startmail-on-effs-secure-messaging-scorecard) | [NO](https://support.startmail.com/index.php?/Knowledgebase/Article/View/520/2/startmail-on-effs-secure-messaging-scorecard) | 
| **Threema**  | YES | YES| [YES](https://threema.ch/es/faq/levels_expl) | [YES](https://threema.ch/es/faq/why_secure) | [YES](https://threema.ch/es/faq/source_code) | [YES](https://threema.ch/press-files/2_documentation/cryptography_whitepaper.pdf) | [NO (Last Audit on 2015)](https://threema.ch/en/faq/code_audit)   |
| **Viber**  | YES | [YES](https://support.viber.com/customer/en/portal/articles/2017401-viber-accounts-security-and-encryption) | [YES](https://support.viber.com/customer/en/portal/articles/2017401-viber-accounts-security-and-encryption) | [YES](https://www.viber.com/security-overview/) | [YES](https://github.com/wireapp/wire) | [YES](https://www.viber.com/security-overview/) | NO (Last Audit on 2014)  |
| **Whatsapp**  | YES | YES| YES| YES| NO| YES|  No records of new audit has been found |
| **Wickr**   | YES | YES | YES | YES | [YES](https://github.com/WickrInc/wickr-crypto-c) | [YES](https://www.wickr.com/wickr-messaging-protocol) | [No (Last audit was on 2014)](https://www.wickr.com/blog-archive/2017/5/26/aspect-security-audit) |
| **Wire**  | YES | [YES](https://wire-docs.wire.com/download/Wire+Security+Whitepaper.pdf) | [YES](https://support.wire.com/hc/en-us/articles/207692235-How-can-I-compare-key-fingerprints-) | [YES](https://wire-docs.wire.com/download/Wire+Security+Whitepaper.pdf) | [YES](https://github.com/wireapp/wire) | [YES](https://wire-docs.wire.com/download/Wire+Security+Whitepaper.pdf) | [YES](https://wire-docs.wire.com/download/Wire+Audit+Report.pdf)  |



### Apps not included:
+ *AIM*: [AIM has been discontinued as of December 15, 2017](https://help.aol.com/articles/aim-discontinued)
+ *TextSecure*: Merged with RedPhone - Now *Signal*
+ *Mxit*: [Terminated](https://businesstech.co.za/news/mobile/139225/mxit-is-officially-dead/)
+ *EbuddyXMS*: Last updated in 2015
