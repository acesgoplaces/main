# ACES TWO by ACES Go Places
A group of 3 ex-Home Team NSFs who are passionate about improving ACES with geolocation functions so that ACES can Go Places.

### Problem Statement
Currently, SCDF receives 995 calls from concerned callers who are usually far away from the incident location or are passing by in moving vehicles. 
This means that SCDF is unable to pinpoint the exact incident location to our ground officers attending to these cases. 
This results in a loss of precious time, where those few minutes in finding out the exact location of the fire, or the subject threatening to jump might mean life and death. 

## Contents
1. [ACES TWO](#ACES-TWO)
1. [How it works?](#How-it-works?)
1. [scdf.tech webpage](#scdf.tech)
1. [Video Demo](#video-demo)
1. [Future Improvements/ Extensions](#future-improvements)
1. [Resources](#resources)

## ACES TWO
### How it works? (Architecture)
ACES TWO uses a separate webpage to pull important data from the caller's phone.
Such important data include Date and Time, current GPS location and direction of where the phone is facing, which helps SCDF to create a proper documentation of the case file onto ACES, rather than having our 995 Dispatchers manually typing out as is the current situation. This frees up our 995 Dispatchers to do more important tasks like assessing the nature of the incident. 

### scdf.tech webpage (Live demo/Getting Started)
*insert pic


The SMS link that will be sent to callers will bring them to the scdf.tech webpage. The webpage will first ask the caller to send their current GPS location data and direction of where their phone is facing for to the case file on ACES. In the event, where further information from the caller is needed in assisting our 995 Dispatchers to ascertain the nature of the incident, there are submission links at the bottom to allow callers to take photos and videos to upload onto ACES. In the submission links, the caller will be prompted to aim the incident location at the centre of their camera. This will help ACES TWO to narrow down the possible incident locations from the field-of-view of the caller.

[scdf.tech](https://scdf.tech)

### Video Demo
[Demo on YouTube](https://youtube.com)

### Future Improvements/ Extensions
#### Speech-to-Text capabilities
By tying ACES TWO with speech-to-text capability, additional information provided by the caller (i.e. description of what's on fire) can be cached and displayed to the 995 Dispatcher. This would ensure that our 995 Dispatchers will be able to understand the caller and have enough capacity to handle multiple tasks all at once.

#### Management of False Alarms
Most industrial and commercial buildings in Singapore are equipped with Decentralised Alarm Monitoring Systems, which transmits the signal from an activated fire alarm to SCDF, who then activates the relevant appliances to the incident. This improves the speed of response and serves as an early-warning system to prevent incidents from escalating to a more serious level. However, false alarms due to  malfunctions, accidents, and even environmental factors (rainy days) result in precious emergency resources being wasted, as  crews are still required to remain on scene to track down the level and zone where the alarm originated. Through ACES TWO, SCDF Operations Centre can directly contact the building Fire Safety Manager or other on-duty personnel through the sms link to verify through photographic or video evidence of the False Alarm, and allow crews to return to base earlier.

[Source: https://www.scdf.gov.sg/docs/default-source/scdf-library/fssd-downloads/fsm-briefing-2017---fsm-perspective-on-false-alarms-and-practical-approach-to-fire-alarm-activation.pdf]

This function can be extended to residential premises as well. False Alarms at residential premises are mainly from Members-Of-Public (MOP) who are very concerned because of loud sounds, foul smells, or white smoke in their residential area. However, these may be a result of rotting food (perhaps due to improperly closed fridge doors) or incense smoke. When a call is received from a MOP who is not the premise owner, an SMS link can be sent to the premise owner to verify if there is indeed a genuine case of emergency.
Any non-response after a short time or negative response would then trigger the Standard Operating Procedure of activating SCDF officers to respond. A positive response from the premise owner, accompanied with photographic or video evidence would confirm the false alarm and avoid the need to activate precious emergency resources.

In cases where it is not a clear false alarm, such as a burning smell without any smoke, responding SCDF officers would have to make a judgement call of breaking into the house in the event that it escalates into an actual fire. However, this may also result in unnecessary damage to property in the case of a false alarm. ACES TWO can be used to quickly contact the premise owner and obtain more information, such as whether there is any food on the stove, greatly improving sense-making in a highly ambiguous situation. 

### Getting Started

### Resources Used
