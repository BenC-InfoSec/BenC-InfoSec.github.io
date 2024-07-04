
---
layout: post
author: Ben C
tags: [Threat Intelligence, Process]
---

A means for an organisation of any size to begin identifying relevant threats and start on the road to building a threat-informed defence

## Table of contents
- [Table of contents](#table-of-contents)
- [Understand the low level threat](#understand-the-low-level-threat)
- [Research the industry](#research-industry)
- [Leverage a framework](#using-mitre)
- [Identify feeds](#identify-feeds)
- [Review process](#review-process)


What follows is a series of steps to iteratively improve understanding.

## [Understand the low level threat](#understand-the-low-level-threat)

Firstly, it is necessary to recognise that organisations of any size will attract the attention of two distinct groups, script kiddies and criminals. A script kiddy is a low skilled, inidvidual or unorganised group motivated by the perceived challenge of hacking, gaining notoriety or general malevolence. Criminals however, seek financial gain, are generally better resourced and operate with varying levels of organisation and ability. Those criminal groups that exhibit high levels of organisation are often refered to as Organised Criminal Groups(OCGs). Attempts are often made to track individual OCG activites and the tactics, techniques and procedures (TTPs) they use. It can be said that Script kiddies do have TTPs, and for the purposes of mapping threats it is useful to do so, but these TTPs are more generalised. 

The initial understanding of the threat landscape is therefore that of a hostile environment and the need for resources to be allocated to secure the organisation. Plotting Script Kiddies TTPs on the MITRE ATT&CK Navigator gives the lowest level of threat actors which our organisation should be reviewing defences against. 

MITRE ATT&CK TTPs of Script Kiddies - low level threat
![theme logo](/assets/images/favicon/Script_kiddies_Sub.svg)


## [Understand the organisation](#understand-the-organisation)

In order to begin identifying specific threat actors likely targetting our organisation, a good first step is to identify risk factors. Examples include countries of operation, industry and customer base e.g. perhaps threat actors could wish to target customer firms and therefore our organistion as part of a supply chain attack. While risk factors should be plausible, it is not necessary to attribute likelihood at this stage. 

Next, try to identify threat actors that have targetted these factors and their specific TTPs. One way to do this is by looking at past attacks. Unfortunately, it can be difficult to identify specifics regrding previous attacks. Often there was limited information publicly released and victims are usually reluctant to share. Research broadly and include industry publications. There have however, been some high profile take downs of criminal groups which have shed light on their activites. One notable case is that of $LAPSUS


MITRE ATT&CK TTPs of Organised Criminal Groups - Mid level threat
![theme logo](/assets/images/favicon/LAPSUS_G1004_Tech.svg)


At this stage, it is likely that Advanced Persistent Threats (APTs) will be identified. These actors are state or state sponsored with high ability levels and resources. Their objectives are political or economic. 

If  

Criminal
MITRE ATT&CK TTPs of Organised Criminal Groups - Mid level threat

Use MITRE ATT&CK to see which major groups are known to target the factors identified for your organisation. For example, looking for TA targetting the legal sector in the UK and Spain 

Try to identify specific actors known to target the sector.

At this stage, it is not a case of certainty, but forming a starting point for refinement. As you research, try and identify the specific tactics used by those bad actors. 

It can be difficult to identify specifics regrding previous attacks. Often there is limited infomration or victims are reluctant to share. Research broadly and include industry publications. Try to identify specific actors know to target the sector. It is likely that your research will lead you to MITRE ATT&CK...

## [Leverage a framework](#using-mitre)


## [Identify feeds](#identify-feeds)

Donec ex lectus, tempus non lacinia quis, pretium non ipsum. Praesent est nunc, rutrum vel tellus eu, tristique laoreet purus. In rutrum orci sit amet ex ornare, sit amet finibus lacus laoreet. Etiam ac facilisis purus, eget porttitor odio. Suspendisse tempus dolor nec risus sodales posuere. Proin dui dui, mollis a consectetur molestie, lobortis vitae tellus. Vivamus at purus sed urna sollicitudin mattis. Mauris lacinia libero in lobortis pulvinar. Nullam sit amet condimentum justo. Donec orci justo, pharetra ut dolor non, interdum finibus orci. Proin vitae ante a dui sodales commodo ac id elit. Nunc vel accumsan nunc, sit amet congue nunc. Aliquam in lacinia velit. Integer lobortis luctus eros, in fermentum metus aliquet a. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.

## [Review process](#review-process)

Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit. Pellentesque vel lacinia neque. Praesent nulla quam, ullamcorper in sollicitudin ac, molestie sed justo. Cras aliquam, sapien id consectetur accumsan, augue magna faucibus ex, ut ultricies turpis tortor vel ante. In at rutrum tellus.

# Sample heading 1
## Sample heading 2
### Sample heading 3
#### Sample heading 4
##### Sample heading 5
###### Sample heading 6

Mauris viverra dictum ultricies. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod.

## Lists

Unordered:

- Fusce non velit cursus ligula mattis convallis vel at metus[^2].
- Sed pharetra tellus massa, non elementum eros vulputate non.
- Suspendisse potenti.

Ordered:

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
