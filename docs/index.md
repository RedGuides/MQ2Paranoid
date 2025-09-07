---
tags:
  - plugin
resource_link: "https://www.redguides.com/community/resources/mq2paranoid.154/"
support_link: "https://www.redguides.com/community/threads/mq2paranoid.66860/"
repository: "https://github.com/RedGuides/MQ2Paranoid"
config: "MQ2Paranoid.ini"
authors: "vzmule, eqmule, pms"
tagline: "Tells when someone zones in and out."
---

# MQ2Paranoid

<!--desc-start-->
This plugin sends a visual alert when someone zones in and out of your current zone. 

<!--desc-end-->

## Commands

<a href="cmd-para/">
{% 
  include-markdown "projects/mq2paranoid/cmd-para.md" 
  start="<!--cmd-syntax-start-->" 
  end="<!--cmd-syntax-end-->" 
%}
</a>
:    {% include-markdown "projects/mq2paranoid/cmd-para.md" 
        start="<!--cmd-desc-start-->" 
        end="<!--cmd-desc-end-->" 
        trailing-newlines=false 
     %} {{ readMore('projects/mq2paranoid/cmd-para.md') }}

## Settings

Example MQ2Paranoid.ini

```ini
[Settings]
Enabled=on
Enter=on
Exit=on
Chat=on
Popup=on
Delay=7
```
