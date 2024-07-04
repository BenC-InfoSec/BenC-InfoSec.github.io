
---
layout: post
author: Ben C
tags: [Threat Intelligence, Process]
---

A means for an organisation of any size to begin identifying relevant threats and start on the road to building a threat-informed defence

## Table of contents
- [Table of contents](#table-of-contents)
- [Understand the low level threat](#understand-the-low-level-threat)
- [Understand the medium level threat](#understand-the-medium-level-threat)
- [Leverage a framework](#using-mitre)
- [Identify feeds](#identify-feeds)
- [Review process](#review-process)


What follows is a series of steps to iteratively improve understanding.

## [Understand the low level threat](#understand-the-low-level-threat)

Firstly, it is necessary to recognise that organisations of any size will attract the attention of two distinct groups, script kiddies and criminals. A script kiddy is a low skilled, inidvidual or unorganised group motivated by the perceived challenge of hacking, gaining notoriety or general malevolence. Criminals however, seek financial gain, are generally better resourced and operate with varying levels of organisation and ability. Those criminal groups that exhibit high levels of organisation are often refered to as Organised Criminal Groups(OCGs). Attempts are often made to track individual OCG activites and the tactics, techniques and procedures (TTPs) they use. It can be said that Script kiddies do have TTPs, and for the purposes of mapping threats it is useful to do so, but these TTPs are more generalised. 

The initial understanding of the threat landscape is therefore that of a hostile environment requiring resources to be allocated to secure the organisation. Plotting Script Kiddies TTPs on the MITRE ATT&CK Navigator gives the lowest level of threat actors which our organisation should be reviewing defences against. 

MITRE ATT&CK TTPs of Script Kiddies - low level threat
![theme logo](/assets/images/favicon/Script_kiddies_Sub.svg)


## [Understand the medium level threat](#understand-the-medium-level-threat)

In order to begin identifying specific threat actors likely targetting our organisation, a good first step is to identify risk factors. Examples include countries of operation, industry and customer base e.g. perhaps threat actors could wish to target a customer and therefore our organistion as part of a supply chain attack. While risk factors should be plausible, it is not necessary to attribute likelihood at this stage. 

Next, try to identify threat actors that have targetted these factors and their specific TTPs. One way to do this is by looking at past attacks. Unfortunately, it can be difficult to identify specifics regrding previous attacks. Often there is limited information publicly released and victims are usually reluctant to share. Research broadly and include industry publications. There have however, been some high profile take downs of criminal groups which have shed light on their activites. One notable case is that of $LAPSUS and CISA have produced a detailed and very interesting [review](https://www.cisa.gov/sites/default/files/2023-08/CSRB_Lapsus%24_508c.pdf). The group is also listed on the MITRE ATT&CK website where a Navigational layer can be [downloaded](https://attack.mitre.org/groups/G1004/G1004-enterprise-layer.json). It is possible that this group has been disbanded by law enforcement, though the TTPs identified, alongside the insight into its operations make it a very good general representation of the criminal threat. Still, if the identified risk factors for your organsiation do not match the targeting history of Lapsus$ then research other criminal groups.

Plotting LAPSUS$ TTPs on the MITRE ATT&CK Navigator gives a medium level threat actor which our organisation should be reviewing defences against. 


MITRE ATT&CK TTPs of Organised Criminal Groups - Mid level threat
![theme logo](/assets/images/favicon/LAPSUS_G1004_Tech.svg)


We now, for most small organisations at least, have a general understanding of the TTPs potentially used by the majority of threat actors targetting it. Advanced Persistent Threats (APTs), actors who are state or state sponsored with high ability levels and resources, represent the most formidable, if not the most numerous threat an organsition could face. These groups are often politically or econmically motivated and deploying sufficient resources to mitigate their threat is likely to need significant resources.

Utilising MITRE ATT&CK again and researching the threat factors which APT groups have historically targeted can help identify relevant groups. For example, Lazarus Group

MITRE ATT&CK TTPs of APT Lazarus - Advanced level threat
![theme logo](/assets/images/favicon/Lazarus_Group_G0032.svg)

## [Review process](#review-process)


1. Quisque arcu felis, laoreet vel accumsan sit amet, fermentum at nunc.
2. Sed massa quam, auctor in eros quis, porttitor tincidunt orci.
3. Nulla convallis id sapien ornare viverra.
4. Nam a est eget ligula pellentesque posuere.

## Blockquote

The following is a blockquote:

> Suspendisse tempus dolor nec risus sodales posuere. Proin dui dui, mollis a consectetur molestie, lobortis vitae tellus.

## Thematic breaks (<hr>)

Mauris viverra dictum ultricies[^3]. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod. **You can put some text inside the horizontal rule like so.**

---
{: data-content="hr with text"}

Mauris viverra dictum ultricies. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod. **Or you can just have an clean horizontal rule.**

---

Mauris viverra dictum ultricies. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod. Or you can just have an clean horizontal rule.

## Code

Now some code:

```
const ultimateTruth = 'follow middlepath';
console.log(ultimateTruth);
```

And here is some `inline code`!

## Tables

Now a table:

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## Images

![theme logo](http://www.abhinavsaxena.com/images/abhinav.jpeg)

This is an image[^4]

---
{: data-content="footnotes"}

[^1]: this is a footnote. You should reach here if you click on the corresponding superscript number.
[^2]: hey there, don't forget to read all the footnotes!
[^3]: this is another footnote.
[^4]: this is a very very long footnote to test if a very very long footnote brings some problems or not; hope that there are no problems but you know sometimes problems arise from nowhere.
