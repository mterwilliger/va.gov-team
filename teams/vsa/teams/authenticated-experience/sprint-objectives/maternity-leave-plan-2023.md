# Samara's 2023 maternity leave plan

**Last updated: March 20, 2023**

Roughly, this will be some time between March - June of 2023, depending on when the baby arrives.

## [Long-term planning spreadsheet](https://docs.google.com/spreadsheets/d/1EN2Z0MPLZ-6qAS3S4q6uiwCekSU1daysJkykDs5bPCs/edit#gid=1487111095)

This was last updated by Samara in March 2023. It is meant to change, be flexible, and grow over time depending on how things shake out, so please don't take this as an unchangeable plan.

## OCTO replacement

My OCTO replacement will be Chante Lantos-Swett. She is @Chante in Slack, and her email is chante.lantosswett@va.gov.

Mikki Northuis (@Mikki Northuis in Slack; michelle.northuis@va.gov) is running point just on the logged-in IA/nav work. Liz can go to either Mikki or Chante with questions about this.

### Things Chante will/won't be doing

Chante is going to be much more light-touch with our team than I am, given that she's already got a full time job. You can expect her to:

- Meet with PMs on a regular cadence
- Attend a standup a week
- Attend high-priority stakeholder meetings
- Field work requests for our team, and help the team figure out whether or not to purse these requests, as well as if the team has bandwidth
- Act as a liaison betweent OCTO and the team

Chante will NOT being doing any of the following:

- Attending every team meeting
- Detailed planning
- Writing tickets
- Validating tickets

## Work we need to wrap up

### [My VA audit updates](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/identity-personalization/my-va/2022-audit#readme)

- **Status**: Pre-launch; Should launch early in April 2023 if everything stays on track.
- [Long-term planning](https://docs.google.com/spreadsheets/d/1EN2Z0MPLZ-6qAS3S4q6uiwCekSU1daysJkykDs5bPCs/edit#gid=923468617)

## Top priorities

These projects are the top priorities, as they align with the top OCTO objectives for the year:

### [Onsite notifications V2: Scale notifications feature](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/identity-personalization/onsite-notifications/notifications-v2#readme)

- **OCTO objective**: Enhance Veterans' personalized online experience
- **Status**: Next steps are up in the air, as we are trying to figure out if any of the existing VANotify notifications are good candidates to incorporate into VA.gov.
- [Long-term planning](https://docs.google.com/spreadsheets/d/1EN2Z0MPLZ-6qAS3S4q6uiwCekSU1daysJkykDs5bPCs/edit#gid=1904788724)

Priorities for this quarter are [notification center discovery](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/onsite-notifications/2023-scaling-onsite-notifications/notification-center-discovery/samara-initial-thoughts.md) and [implementing the new onsite notification design](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/onsite-notifications/update-design-system-component/README.md).

### [Notification preferences: Updates to add email as a channel](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/identity-personalization/profile/notification-preferences/discovery-and-research/add-email-channel)

- **OCTO objective**: Enhance Veterans' personalized online experience; Support MHV health migration
- **Status**: Discovery and design complete; Backend and frontend code updates are next.
- [Long-term planning](https://docs.google.com/spreadsheets/d/1EN2Z0MPLZ-6qAS3S4q6uiwCekSU1daysJkykDs5bPCs/edit#gid=1678753305) -- Note that I have not been able to complete detailed planning because next steps depend on some level of technical discovery and estimation. The team + new profile PM will need to do this.

Why we are adding email as a channel: We need to be able to support email as a channel in order to support MHV notification preferences, and notification preferences from other partners that may require email. This is critical work.

In order to be able to add email as a channel, we need to do two things: add the default-send indicator, and update the UI to move from a radio button to checkbox design. We'll likely complete the default send work in Q2 of the calendar year, and start the UI updates in Q2 but launch them in Q3 of the calendar year.

Behind the scenes, Samara is coordinating backend implementation of the MHV notification preferences in VA Profile. Once those have been implemented in VA Profile and MHV, we should be in good shape to add them to our UI.

### [Generative logged-in IA/navigation research](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/ia-and-navigation/2023-generative-logged-in-research)

- **OCTO objective**: Refresh the VA.gov homepage and information architecture
- **Status**: User research planning; User research; Generating a report that summarizes all research activities.
- [Long-term planning](https://docs.google.com/spreadsheets/d/1EN2Z0MPLZ-6qAS3S4q6uiwCekSU1daysJkykDs5bPCs/edit#gid=189401760)

In Q2 of the calendar year, we'll be running some generative user research to uncover what problems people have navigating the logged-in experience. After research synthesis, we'll work with Mikki and Chante to figure out next steps.

**Note**: Liz Lantz, who is primarily in the profile half of the portfolio, will be leading this from the auth exp team perspective. However, this is not solely a profile project. This work is more holistic and sits outside of the My VA and Profile division.

## Necessary maintenance

This doesn't align with OCTO objectives, but this is work we have to get done in order to continue supporting critical existing integrations:

### EVSS > Lighthouse migrations

#### [Update direct deposit for comp & pen section of the profile](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/direct-deposit/evss-lighthouse-migration/README.md)

- **Status**: Build is almost done; this needs to be thoroughly tested before a monitored, phased launch.
- [Long-term planning](https://docs.google.com/spreadsheets/d/1EN2Z0MPLZ-6qAS3S4q6uiwCekSU1daysJkykDs5bPCs/edit#gid=378891642)

For Q2 of the calendar year, we'll be ready to conduct QA, go through pre-launch activities, and launch the updated integration. 

#### Update the claim status section of My VA

- **Status**: Hasn't started yet, but should be ready to start once Derrick is fully onboarded.
- [Long-term planning](https://docs.google.com/spreadsheets/d/1EN2Z0MPLZ-6qAS3S4q6uiwCekSU1daysJkykDs5bPCs/edit#gid=378891642)

Assuming we have availability, we can leverage the updated claim status integration that now relies on Lighthouse so that My VA pulls data from there instead of EVSS.

#### Update the disability rating section of the nametag and VA.gov profile

- **Status**: The backend migration will be done by the [benefits disability experience team](https://dsva.slack.com/channels/benefits-disability-experience). As of March 2023, Matt Self says they are still in discovery, but it's possible they'll begin work while I am on leave. Our team needs to keep up on this work, as we will need to migrate our frontend connections for the nametag and the profile as soon as they are done.
- [Long-term planning](https://docs.google.com/spreadsheets/d/1EN2Z0MPLZ-6qAS3S4q6uiwCekSU1daysJkykDs5bPCs/edit#gid=378891642)

## What about other work?

We already have a packed quarter for when I am out. If there are requests that come in, the OCTO lead(s) should work with the PMs to slot those in to planning **if time allows**. If the team is full and does not have bandwidth, do not hesitate to communicate that to stakeholders and figure out on what timeline we might be able to get to the work. The auth exp team is very capable, and I trust them to communicate when they do and do not have bandwidth accurately.

### VA Profile 

This is work I am aware is coming down the pipeline, I just don't know when.

- **Notification preferences for "early comms" work (ie. eBenefits prefs that need to move over)** -- This will likely be very straightforward. If VA Profile just needs some copy for the new preference(s) and for us to implement a feature toggle, this should be slated in pretty easily. If they need more comprehensive work (I don't think they do), please plan accordingly to other priorities.
- **Telephone number validation** -- This will likely require interface and code changes, and I don't know when the team will have bandwidth. We can get to this eventually, but if this needs to wait until I'm back, so be it. Please work with the team to scope this work, and then only put it into planning if there are available people. If not, let VA Profile know we need to hold off for a few sprints.

### Health apartment

This is work I am aware is coming down the pipeline, I just don't know when.

- **Notification preference for including PHI/PII in appointment reminders** ([Slack](https://dsva.slack.com/archives/C909ZG2BB/p1677865410217999)) -- MHV may need a preference for appointment reminders that allows people to opt-in/out-of showing PHI/PII in appointment reminders. Depending on what kind of UI and code updates are needed from our team, this might be heavier lifting that our current process for adding a new text message permission.
- **Adding other health data to the VA.gov profile** -- I've been talking to Lauren/Coulton/Kay/Patrick about a bunch of health data VA.gov will likely need to eventually support to fully support the health apartment. Some of this may need to live in the profile. I don't know how soon we'd need to work on any of this, but we should keep an eye on this and slate any definite/necessary projects in as bandwidth allows. Most of our other work supports the health apartment long-term, so we should not drop any of our top priorities for this.

## For OCTO

### The auth experience team

Right now, the auth experience team is roughly divided into two halves: the half that primarily works on the My VA dashboard and onsite notifcations work, and the half that works on all of the products in the VA.gov profile.

However, this is not a strict binary, and some people float between efforts depending on capacity needs. We should staff work while I'm out according to overall portfolio priorities, not necessarily which half of the team people are usually on.

#### Team members

- **Ana (AJ) Jakabcin** - PM for the My VA/onsite notifications half of the team. **AJ does not manage profile work, nor does she (or do I expect her to) have familiarity with that half of the portfolio**.
- **Berni Xiong** - Delivery manager; supports both halves of the team.
- **Liz Lantz** - Senior designer; Working on the logged-in IA/nav research for now, but has primarily worked on the profile.
- **Angela Agosto** - Designer primarily supporting My VA and onsite notifications.
- **Florence McCafferty** - Designer primarily supporting the profile, or floating as needed to other priorities.
- **Allison Lu** - Frontend developer primarily supporting My VA and onsite notifications.
- **Adam Whitlock** - Frontend developer primarily supporting the profile.
- **Tom Harrison** - Backend developer primarily supporting the profile, but has historically pitched in on the My VA half of the portfolio has needed.
- **Derrick Ellerbie** - Full stack developer, starting out supporting the My VA dashboard, but can float as needed to other priorities. 

Unfortunately, **we are still without a profile PM since the contract switch in December 2022**, which is a huge hole/risk to have that role open while I am out. I imagine someone will start while I am on leave. Berni Xiong (delivery manager) is responsible for onboarding the new PM with the help of the profile team.

### Efforts I'm tapped into

#### MHV: Integrating their interface with VA Profile

In order for VA.gov to incorporate the MHV notification preferences into our interface, MHV has to integrate their interface with the VA Profile backend for both contact information and notification preferences. I need someone on the OCTO side of things to keep up with Carnetta and the VA Profile team (Mike Richards etc) to make sure the MHV side of things is moving along. VA Profile's work on this is easy -- they already support contact info, and they have been able to get the MHV notification preferences in the backend fairly easily. Keeping up on what MHV is doing and making sure that is moving along is the harder part, and is what is a large dependecy for us to update the VA.gov interface.

#### VEO transition efforts

VEO conducted a huge research effort last year around veteran transtion. In the fall, they put together a cross-departmental working group to figure out how to improve transition. Their solution is a checklist-based app, and they are trying to figure out how to get someone either at DoD or VA to take this on at the moment. I've been going to these meetings as a rep from VA.gov, but I have let them know I am not available until after my maternity leave at this point. While it is unclear what kind of involvement VA.gov might have going forward, they'll likely want someone from our team tapped into that work. Mike Land might be picking this up, or potentially Steve Kovacs.

### Stakeholders for OCTO replacement(s) to be aware of

#### VA Profile

- Mike Richard (Michael.Richard2@va.gov) -- Mike is a contractor PM for VA Profile, and he's usually the first person I go to re: VA Profile efforts.
- Barbie Flowers (barbara.flowers3@va.gov) -- VA lead for VA Profile.
- Joshua Lindsey (jlindsey@meetveracity.com) -- Lead VA Profile architect for technical questions/issues.

#### MHV

- Carnetta Scruggs (carnetta.scruggs@va.gov) -- I've been keeping in touch with Carnetta re: the work MHV needs to do to connect to VA Profile. There's not much we can actually do on this front -- MHV has to do the work -- but it would be helpful to check in with Carnetta periodically on this. VA Profile can also help keep my replacement updated on that effort.

#### VANotify

Both halves of the team work a fair bit with VANotify. That's Bev, obviously, and also Melanie Jones (melanie.jones@oddball.io).

#### Lighthouse

These are the folks overseeing the EVSS > Lighthouse migration:

- Lee Helmer (lee.helmer@adhocteam.us) -- Lead on the entire EVSS > Lighthouse effort.
- Lorri Glover (glover_Lorri@bah.com) -- Involved with the direct deposit migration.
- Greg Feliberty (feliberty_gregory@bah.com) -- Involved with the direct deposit migration.
- Andrew Ramos (ramos_andrew@bah.com) -- Involved with the direct deposit migration.
- Dana Harris (dana.harris@adhocteam.us) -- Involved with the direct deposit migration.
 
#### VEO

I believe Mike Land is now point person for this, but including this info here just in case.

- Jon Pruett (Jonathan.pruett@va.gov) -- VEO transition team.
- Mandy Tepfer (amanda.tepfer@va.gov) -- VEO transition team.

#### Other potential people you might hear from

- Bill Brinley (William.Brinley@va.gov) -- VA lead on something called the "Enhanced Statement of Benefits". They have weekly meetings, which I *do not* attend anymore, but used to be involved in. So, you might hear from him, or the contract lead (Lynn B Jones <lbjones@mitre.org>) on this.

### Meetings for OCTO replacement(s) 

#### Auth experience team meetings

*My VA and onsite notifications*

- **Weekly 1:1 with AJ, My VA PM**: Mondays at 2:00 ET.
- **My VA standup**: Please attend one of these/week. They are currently Monday and Friday at 3:00 ET and Thursday at 1:45 ET.
- **My VA planning**: It's optional if my replacement attends this, but this meeting is at 2:15 ET every other Wednesday.

*Profile*

- **Weekly 1:1 with Berni Xiong, Auth exp delivery manager**: Mondays at 2:30 ET. Feel free to stop having 1:1s with Berni once the profile PM starts. She's been helping with profile efforts while A6 is hiring a profile PM.
- **Profile standup**: Please attend one of these/week. They are currently Monday and Friday at 3:15 ET and Thursday at 2:30 ET.
- **Profile planning**: It's optional if my replacement attends this, but this meeting is at 1:00 ET every other Wednesday.

#### Stakeholder meetings

*Required meetings*

- **MHV on VA.gov weekly standup**: Wednesdays at 11:30 ET.
- **VA Profile biweekly check-in**: Every other Thursday at 3:30 ET.
- **VANotify biweekly sync**: Every other Tuesday at 2:00 ET.
- **Logged-in IA/nav research and project coordination**: Every Wednesday at 10:00 ET with Mikki and Chante (and if Mikki or Chante replaces me in any capacity, they already know about this meeting!).

*Meetings to be aware of*
 
- **VA.gov and Lighthouse sync**: Every other Thursday at 2:00 ET. This meeting is a touchpoint for those of us who are moving integrations from EVSS > Lighthouse. Tom Harrison -- BE developer on auth experience -- usually attends this, so I don't think this is necessary for my replacement unless there are specific issues or questions.
- **eBenefits "Early Comms" meeting**: Every other Tuesday at 2:30 ET. This has to do with notifications/preferences around notifications that lived in eBenefits. These have been going on for months, and there has been little movement, so I would say my replacement does not need to attend these unless it becomes clear that a new preference needs to be added to the VA.gov profile. **Bev can likely keep you posted on any necessary updates from this meeting.**
- **VA Profile/QuickSubmit notifications call**: Every Tuesday at 3:30. This has to do with a notification and preference around a platform called "QuickSubmit", which I believe is related to the claims process. **Bev can likely keep you posted on any necessary updates from this meeting.**
- **VEO transition calls**: One is biweekly every other Tuesday at 3:00 ET; the other is every week on Thursdays at 1:00 ET. **Mike Land is attending this stuff at least while I'm out, potentially long-term, so don't worry about this**.
