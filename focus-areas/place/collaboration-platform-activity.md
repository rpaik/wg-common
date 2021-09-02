# Collaboration Platform Activity

### This metric is a release candidate. To comment on this metric please see Issue [132](https://github.com/chaoss/wg-common/issues/132). Following a comment period, this metric will be included in the next regular release.

Question: What is the count of activities across digital collaboration platforms used by a project?

## Description
Open source projects use many different digital communication and collaboration platforms. These platforms may include email, social media, chat applications, and code management technologies. This metric is a measure of where and how much message activity is occurring across collaboration platforms.

## Objectives
Understand where the community is collaborating.
To develop insights related to the processes followed by each project, which are more likely to be accurate if our review of the communication logs is as complete as possible.
Demonstrate how open and transparent a project is.
Help people find the appropriate place to make contributions and connect with the project.
Help project maintainers determine the optimal number of channels to effectively and efficiently share information while allowing contributors to connect in the way that works best for them
Find the lowest barrier channels for engagement
Inform other metrics like: [Burstiness](https://chaoss.community/metric-burstiness/), [Project Velocity](https://chaoss.community/metric-project-velocity/), [Social Listening](https://chaoss.community/metric-social-listening), [Activity Dates and Times](https://chaoss.community/metric-activity-dates-and-times/), [Chat Platform Inclusivity](https://github.com/chaoss/wg-diversity-inclusion/issues/318)

## Implementation
The unit of data collection is the individual activity on a platform. Metadata related to the metric can include:
* Timestamp
* Sender
* Threaded/Non-Threaded Platform
* Data Collection Date
* Platform message identifier

### Aggregators
* Number of people
* Number of messages
* Number of comments
* Type of Channel (mailing list, irc, and so on)
* Activity per day of the week


### Visualizations

![GrimoireLab Implementation](images/collaboration-platforms.png)

https://chaoss.biterg.io/app/kibana#/dashboard/ab68fe20-17f2-11e9-872f-e17019e68d6d

### Tools Providing the Metric
* Orbit.love is a community management platform that captures this for a few channels: https://docs.orbit.love/docs/adding-activities
* GrimoireLab
* Augur


## References
* Related metric: https://chaoss.community/metric-chat-platform-inclusivity/
* Related metric: https://chaoss.community/metric-issues-new/

## Contributors

* Elizabeth Barron
* Sean Goggins
* Matt Germonprez
* Danial Isquierdo
* Dawn Foster
* Beth Hancock
* Kevin Lumbard