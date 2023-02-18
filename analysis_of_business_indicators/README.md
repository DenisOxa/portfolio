# Project name: Analysis of business indicators

## Discription
**Context**

App Procrastinate Pro+ has been losing money for the past few months, despite large investments in advertising.

Target - sort out the reasons and help the company to become a plus

**Data contains:**

There are three datasets available. Data about users attracted from May 1 to October 27, 2019

*visits_info_short.csv* - stores a server log with information about site visits

*orders_info_short.csv* — contains order information

*costs_info_short.csv* — advertising spending information

Structure of *visits_info_short.csv*:

- User Id — unique user ID,
- Region — country of user,
- Device — user device type,
- Channel — идентификатор источника перехода,
- Session Start — session start date and time,
- Session End — session end date and time.

Structure of *orders_info_short.csv*:

- User Id — unique user ID,
- Event Dt — date and time of purchase,
- Revenue — order price.

Structure *costs_info_short.csv*:

- dt — date of the campaign,
- Channel — advertising source ID,
- costs — spending on this campaign.

The **goal** of the project:
- Determining the profile of users (where they come from and what devices they use)
- Determining the cost of user acquisition
- Check cost recovery
- Identify factors that hinder customer acquisition.

## Key results:

1.
- The largest market is the US market. It also has the highest share of paying users 6.9%
- Most users use iPhone, the share of paying users of this device is 6.2%. MAC has the highest share of paying users - 6.4%
- Most of the clients came from channels organic, FaceBoom, TipTop, OppleCreativeMedia, LeapBob. Нhowever, the share of paying users is highest for channels FaceBoom, AdNonSense, lambdaMediaAds, TipTop.

2.
- Total Marketing Spend 105497.3
- TipTop, FaceBoom - channels with the highest costs - 51.9% and 30.75% respectively. TipTop costs have only increased over time
- The highest CAC for the same companies.(TipTop - 2,8; FaceBoom - 1,1)

#### Devices

Issues: On the horizon 14 days, the costs do not pay off for iPhone, Mac and Android

#### Country

Issues: US ROI not reaching payback level.

#### Channels

Issues: AdNonSense, FaceBoom and TipTop channels do not reach the payback level. The main disadvantage of the TipTop channel is an increase in CAC, FaceBoom and AdNonSense - low retention

Recommendation: In general, promising investment channels are lambdaMediaAbs, RocketSuperAds, YRabbit. TipTop channel costs need to be reduced as they do not pay off

#### Considering the US separately

Issues:
- The increase in CAC did not lead to a significant increase in paying users.
- The main attraction channels are FaceBoom and TipTop, they are the most spent funds, but the ROI level is not achieved. (TipTop - due to high CAC, FaceBoom - due to low payback)

Recommendation: In the US market, the channels RocketSuperAds, MediaTornado and YRabbit look like suitable for investment, the first one looks the most promising for investment.

#### Consideration of Europe

Issues AdNonSense channels not reaching payback level

Recommendation: In Europe, promising channels are lambdaMediaAbs, LeapBob, OppleCreativeMedia and WahooNetBanner
