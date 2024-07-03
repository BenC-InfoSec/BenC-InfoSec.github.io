
---
layout: post
author: Ben C
tags: [Threat Intelligence, Process]
---

A means for an organisation of any size to begin identifying relevant threats and start on the road to building a threat-informed defence

## Table of contents
- [Table of contents](#table-of-contents)
- [Understand the organisation](#understand-the-organisation)
- [Research the industry](#research-industry)
- [Leverage a framework](#using-mitre)
- [Identify feeds](#identify-feeds)
- [Review process](#review-process)


What follows is a series of steps to iteratively improve understanding.

Firstly, it is necessary to recognise that organisations of any size will attract the attention of two distinct groups, script kiddies and criminals. A script kiddy is a low skilled, inidvidual or unorganised group motivated by the perceived challenge of hacking, gaining notoriety or general malevolence. Criminals however, seek financial gain and operate with varying levels of organisation and ability. As such, the initial understanding of the threat landscape is that of a hostile environment and the need for resources to be allocated to securing the organistion.

Plotting some well known Tactics, Techniques and Procedures of low level threat actors on the MITRE ATT&CK Navigator gives the first layer of threat which our organisation should be reviewing defences against. 

MITRE ATT&CK TTPs of Script Kiddies
![theme logo](/assets/images/favicon/Script_kiddies_Sub.svg)



## [Understand the organisation](#understand-the-organisation)

Try to identify risk factors that can be used as a basis for researching threat actors. Examples include countries of operation and customer base e.g. perhaps threat actors could wish to target customer firms and therefore our organistion as part of a supply chain attack. While risk factors should be plausible, it is not necessary to attribute likelihood at this stage.


## [Research historical exploitation of risk factors](#research-industry)

Try to identify threat actors that have targetted the industry and how. At this stage, it is not a case of identifying specific actors with any certainty, instead you are beginning to form a starting point for refinement. As you research, try and identify the specific tactics used by those bad actors. Some example questions are below. 


#### Which companies in the same industry have been attacked, by whom and how?
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
