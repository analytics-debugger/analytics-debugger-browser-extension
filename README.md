<br>
<p align="center">
<a href="https://www.thyungster.com" target="_blank">
<img src="https://www.analytics-debugger.com/wp-content/uploads/2023/05/vector-2.svg" alt="Analytics Debugger" height="250" width="250"/>
</a>
</p>

<p align="center">
Your Single Source of Truth  <b> (SSOT)</b><br/>for debugging analytics implementations
</p>



<p align="center">
<img src="https://img.shields.io/badge/107K-Users-brightgreen" alt="Total Monthly Users">
<img src="https://img.shields.io/badge/10M-Pages Debugged-brightgreen" alt="Total Debugged Pages">

</p>

# Analytics Debugger Browser Extension 
This repository is mean to keep track of Issues / Features Request.


# Help Me Keep Analytics Debugger Free and Updated!

I hope this message finds you well. I need your support to continue providing this service to the analytics community. 

I've developed this free debugging extension to help fellow analysts all around the world to work to identify and rectify issues in their tracking implementations, ensuring accurate data collection and insightful analysis for businesses of all sizes.

## Why Your Support Matters

In today's data-driven world, the accuracy of analytics data is crucial for making informed decisions. However, we understand that not all analytics vendors have the resources to invest in comprehensive debugging tools. 

That's where our free debugging extension comes in. By offering this tool at no cost, we aim to level the playing field and enable businesses, big and small, to access high-quality analytics data.

## How You Can Help

- **Donate/Sponsor**: Your financial support, no matter how small, will go a long way in helping us cover the costs of maintaining and enhancing our debugging extension.

<p align="center">
  <a href="https://github.com/sponsors/thyngster"><img src=https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#white" alt="GitHub Sponsors" /></a>
  <a href="https://ko-fi.com/thyngster"><img src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Ko-Fi" /></a>
</p> 


- **Spread the Word**: Even if you can't make a monetary contribution, you can still support our cause by sharing our project with your network. The more people who know about our free debugging extension, the greater its impact.

- **Feedback and Collaboration**: If you have technical expertise or ideas that could help us improve our extension, please don't hesitate to reach out. We welcome collaboration and feedback from the analytics community.

## Get in Touch

By supporting thisr free debugging extension, you are not only helping analytics vendors ensure data accuracy but also contributing to the broader goal of fostering data-driven decision-making in organizations worldwide.
I'm  truly grateful for any assistance you can provide, whether it's a donation, sharing our project, or collaborating with us. Together, we can make analytics more reliable and accessible for everyone.

If you are a vendor and want your tool integrated on Analytics Debugger, if you have any questions or if you would like to discuss potential collaborations, please feel free to contact us [https://www.thyngster.com/contact](https://www.thyngster.com/contact-me)

# Change Log 
## [v2.4.4] - 2023-09-05
### Added
- Ingestion API
  (previously, markdown-it would likely go into infinite loop instead), #847.
- GTM Errors Monitor
  A new tab on the GTM panel will report any errors originiated from any GTM container
### Fixed
- Floodlights hits not being detected propertly. Added Sales variables reporting on top ( Order, Cost, etc)
- Google Ads parsing was causing a blank page errors depending on the data holded on the hit.
- FIxed Control + Click action on MacOs
- Ringside report was removed on the last version by mistake, now it's again available.
## [v2.4.3] - 2023-09-02
### Added
- Dark Mode
### Fixed
- Adobe Launch report was removed on the last release. Now it's available again
- Multiple bugfixes form previous release
## [v2.4.0] - 2023-08-31
### Added
- Command Palette ( Press Control+Shift+K )
- GA4: Clicking on a Measurment ID shows the current configuration setting ( enabled enhanced measurement trackin info, referrals details, cross domain details, events added, events modified, etc )
- GA4: Recommended events. If the current event is a Google recommended you can control-click it to see the recomemded parameters for it. 
- GA4: PII Data reporting. If any hit or event holds PII data (emails autodetected for now) al alert icon will be shown on the reports
- GA4: Most friend ECC/Items report block
### Improved
- GA4 Reports get a revamp and a bunch on functionalities
- Codebase size reduced by a 11%
- Marketing Pixels data now reported more organized across all vendors
- Added tooltips all around the tool to improve the UX.
- +35 bug fixes 

Older Releases Info >
