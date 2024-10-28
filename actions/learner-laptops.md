---
title: Learner Laptops
description: Poverty is, most of the time, a result of being uninformed about the workings of the world, and the lack of education. Hence, the best thing we can do for someone is to give them a quality education. The most powerful learning tool, is a laptop.
published: 1
date: 2024-10-28T16:03:33.178Z
tags: education, empowerment, laptop, repair, technology, ubuntu
editor: markdown
dateCreated: 2024-10-28T15:27:04.385Z
---

# Learner laptops

## Actors needed

1. a donor of an old laptop
2. a provisioner of the learner laptop
3. an educator/mentor to offer long-term learner support through the provisioned laptop
4. a learner in a country of poverty and no good education

## Outline 

### Donations 

In this initiative, I invite those living in first-world countries to seek out and request *donations of old laptops* through their local makerspace/repair communities.

In case of a places where people are unfamiliar with makerspaces or repair cafes, this can simply be your neighbourhood app/forum/WhatsApp group, your local Facebook group, or a parents' meeting.

### Provisioning

After collecting the laptops, minor upgrades in terms of RAM and a solid-state drive SSD can be performed to boost the performance of the old laptop. Then, Ubuntu 22.04 can be installed.

Unfortunately, a laptop, alone, cannot change the life of a person. Hence, a teacher is needed, who promises to commit themselves to the person(s) to which the laptop is sent.

Once a commited teacher is found, the person provisioning the laptop needs to obtain the following information from him/her:
- Their *TeamViewer's* account credentials (username/password) to link their account permanently to the `teamviewerd` daemon on the laptop, allowing unattended access as well as attended learning sessions.
- The *public certicates* from all the devices the teacher wishes to use to access an always-open, terminal-session on the laptop (similar to SSH access). This is to help the learner install software and fix problems with their Ubuntu system.

In return, the teacher will be handed out this information:
- A master *TeamViewer* password in case the account link does not work to connect to the laptop
- A password for unlocking *TeamViewer's options* on the laptop, if needed
- A root password
- A BIOS screen password, to share it with the learner if needed at any point

The system I advise for provisioning laptops is documented in this article, which is currently on *Medium*:
[Setting Up a Monitored, "Learning Laptop", to be Sent Abroad](https://medium.com/@orwa.diraneyya/setting-up-a-monitored-learning-laptop-to-be-sent-abroad-73f232363e38)

This setup includes accessories, a bag, and a well-designed bootable USB drive to resetting the system if needed, while restoring all the mechanisms of intervention above.

### Teaching

Once the information is exchanged, the laptop can be sent to its final destination, either via post or through an additonal actor: a logistics actor. This can be someone from the local community who is travelling to the target country by plane and willing to carry the laptop along with them.

The teacher must learn how to use the intervention mechanisms shipped wit the laptop, which are the following:
1. [TeamViewer](https://www.teamviewer.com/) for Secure GUI Control
2. [tmate](https://tmate.io/) for Secure Shell Access

Then, the teacher must build a strategy for teaching the learer(s) with multiple tracks:
- Financial management (list of upcoming/past expenses)
- Documentation and clear communication
- A foreign human language, or work on improving the learner's English
- Logical languages (e.g. Markdown, Mermaid charts, etc.)
- Photo editing and vector design (using PhotoGIMP and Inkscape, which are very performant on old laptops running Ubuntu)
- Books (e.g. Rich Dad Poor Dad)

The area of curriculum has infinite possibilities but it is important to focus on the learner(s) and what can be more impactful for them, in their current environment.

It is also important to take into account their ambitions, but also while steering them away from poor habits and role models that push them in the direction of unprofitable hard work, when it is possible (and easy) to earn a living with one's brain, instead.

As the initiative takes off, there can be dedicated channels for educator communication within the realm of long-term teaching of young adults in disadvantaged places.

