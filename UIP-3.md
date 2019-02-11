U°OS Referral System
---------------------------

Design and implementa a referral system for U°OS network.

Key terms:

REFERRER — an account registered at u.community
REFERRAL — an account that is registered through REFERRER's link

Core mechanics:

* Any account registered on the U°OS network with a non-zero Importance can generate a referral link.
* The maximum amount of referral links that a REFERRER generates depends on the amount of resources the REFERRER has on the U°OS network. Basically, the referral links must be backed by resources
* A REFERRAL can only have one referral connection. And consequently, a REFERRAL can only have one referral connection with one REFERRER
* A referral link can only be used once
* A referral link has a time-to-live period
* A referral reward is a set percent from UOS emission for REFERRAL based on REFERRAL's Importance
* The referral system has levels. The reward amount based on the previous bullet decreasing on the distance from the REFERRER
* A fee to the system account is dedcued from the referral reward
* REFERRER can set up a refback — an option to issue part of the referral reward to REFERRAL
* REFERRAL and REFFERER accounts automatically set a mutual FOLLOW
* With the refback option enabled, REFERRAL and REFFERER accounts automatically set a mutual TRUST
* REFERRER allocates additional resources to REFERRAL on registration. This incentivizes using the ref system

Impact
-------

A ref system naturally induces the network growth.
