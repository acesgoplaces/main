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
ACES TWO uses a separate webpage to pull important data from the caller's phone.
Such important data include Date and Time, current GPS location and direction of where the phone is facing, which helps SCDF to create a proper documentation of the case file onto ACES, rather than having our 995 Dispatchers manually typing out as is the current situation. This frees up our 995 Dispatchers to do more important tasks like assessing the nature of the incident. 
### How it works? (Architecture)
The 995 Dispatcher will generate a unique SMS link using <service>, that is tied to the open case file on ACES TWO and be sent to the caller.


Once the link is opened, the caller will be prompted to accept permissions for their geolocation data to be sent to <service>, which also updates ACES TWO.
  
  
If directed by the 995 Dispatcher, the "photo/video" button allows the caller to take live photos of the incident from his current location. This photo/video, along with its geolocation data, will be sent to <service>, which also updates ACES TWO to help narrow down the possible incident location.
  

If directed by the 995 Dispatcher, the "video call" button allows the caller to engage in a video call using <service> with the 995 Dispatcher. This can serve as a live feed for SCDF Ops Centre. 

### scdf.tech webpage (Live demo/Getting Started)
*insert pic


The SMS link that will be sent to callers will bring them to the scdf.tech webpage. The webpage will first ask the caller to send their current GPS location data and direction of where their phone is facing for to the case file on ACES. In the event, where further information from the caller is needed in assisting our 995 Dispatchers to ascertain the nature of the incident, there are submission links at the bottom to allow callers to take photos and videos to upload onto ACES. In the submission links, the caller will be prompted to aim the incident location at the centre of their camera. This will help ACES TWO to narrow down the possible incident locations from the field-of-view of the caller.

[scdf.tech](https://scdf.tech)

### Video Demo
[Demo on YouTube](https://youtube.com)

### Future Improvements/ Extensions
#### Speech-to-Text capabilities
By tying ACES TWO with speech-to-text capability, additional information provided by the caller (i.e. important descriptions such as what's on fire, etc) can be automatically included into the case file on ACES.

#### DECAMS for Residential Premises
SCDF receives many residential fire related calls that are False Alarms each year. These are mainly from Members-Of-Public (MOP) who are very concerned because of some loud sounds, foul smell, white smoke in their residential area. 
For cases where such abnormalies are known to be from another unit, SCDF can actually trigger an SMS link to the premise owner to verify if there is indeed a genuine case of emergency.
Any non-response after a set time or negative response would then trigger the Standard Operating Procedure of activating SCDF officers to respond. 
Else, a positive response from the premise owner would avoid the need of having to activate precious emergency resources.

/* False Alarm calls for fire incidents is unattended cooking. And when owners are not present at home, responding SCDF officers would then have to make a judgement call of breaking into the house in the event that it escalates into an actual fire. */

### Getting Started

### Resources Used
