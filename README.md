## openjdk

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Set up (the default or a specific update version of) openjdk Debian-like systems.

#### Requirements

None

#### Variables

* `openjdk_versions`: [default: `[{version: 'default', set_as_default: true}]`]: Oracle java version(s) to install
* `openjdk_versions.{n}.version`: [required]: Version to install (`8`, `9`, `default`)
* `openjdk_versions.{n}.set_as_default`: [default: `false`]: Whether or not to set as default (does not work for `version` `default`)

#### Dependencies

None

#### Example(s)

##### Simple

```yaml
---
- hosts: all
  roles:
    - openjdk
```

##### Advanced

```yaml
---
- hosts: all
  roles:
    - openjdk
  vars:
    openjdk_versions:
      - version: 8
      - version: 9
        set_as_default: true
```

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
