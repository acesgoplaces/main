# Position Locator [ACES](https://web.archive.org/web/20200614085318/https://www.rrmediagroup.com/News/NewsDetails/NewsID/5172) (PLACES) by [ACES Go Places](https://en.wikipedia.org/wiki/Aces_Go_Places_(film_series))

PLACES 

<details>
  <summary>Who are we?</summary>

  We are three Home Team NSmen who are passionate about improving systems and processes through the use of technology.
</details>

<details>
  <summary>
    Problem Statement 4: Preventing the Spread
  </summary>

  When an incident occurs, there are usually multiple simultaneous callers who all have information about. 

  If there are no clear landmarks, pinpointing an exact location within a large building, or along a long expressway can be difficult. Callers who simply happen to be in the area often do not know the exact address of the incident area. They might also be far away or passing by in moving vehicles.
  
  In certain locations, such as along highways, in parks/forested areas, and even out at sea, there are few or no reference addresses, so an operator might have great difficulty accurately identifying the location of the incident.
  
  For events such as collapsed buildings, chemical leaks, large fires, or other large scale events, it is also dangerous for callers to approach the incident site to gather information, and thus they can only observe at a distance.
  
  Without accurate location information, ground officers attending to the cases might be unable to locate the victims, and might have to spend precious minutes searching the general area. Those few minutes can make the difference between life and death.

  PLACES aims to overcome these challenges by providing a way for callers to communicate to SCDF the location, extent and severity of an incident through their location data, photos, and videos. Through the compass and gyroscope in the phone, the azimuth to the incident can be plotted from their location (longitude, latitude, bearing), allowing SCDF Operations Centre to triangulate the location of the incident from two or more callers even in the absence of landmarks and reference points. The address and relevant details of the affected premises can then be extracted based on the triangulated position. By using an SMS link, it eliminates the need for users to download an additional application during an emergency, and enables anyone with a camera-equipped smartphone to provide accurate and timely information to SCDF. This also allows the Operations Centre to distinguish between multiple callers describing the same incident, or if there are two separate incidents or fire points occuring at the same time, enabling better sense-making and use of limited resources. 

  As a result, PLACES allows SCDF to quickly identify, pinpoint, and gather information on events from the onset and prevent them from escalating further and causing greater damage to life and property. By allowing anyone in the vicinity and not just those who have downloaded myResponder or SGSecure apps to act as the first "eyes on the ground" for emergency responders, community resilience is also improved, as tourists, foreigners and migrant workers can also participate in the emergency response process. In a world that is increasingly volatile, uncertain, complex and ambiguous, with multiple challenges ahead, PLACES is a solution that leverages technology to tap on the community for improved sense-making and faster response, not if, but when events occur.
</details>

## Contents
1. [How it works](#How-it-works?)
1. [Live Demo](#scdf.tech)
1. [Video Demo](#video-demo)
1. [Future Improvements/ Extensions](#future-improvements)
1. [Resources](#resources)

### How it works? (Architecture)
When a caller calls 995 but is uncertain of the exact location, a link can be sent to the caller via SMS. This link directs the caller to a separate webpage which pulls important data from the caller's phone. Such important data include Date and Time, current GPS location and direction where the phone is facing. On the webpage, a live map shows the current location of the caller and a narrow isoceles triangle shows the orientation of the phone and the field-of-view. This intuitive set-up, similar to the interface in a commonly-used navigation application, allows the caller to quickly verify that the location and bearing to the incident site is correct. The caller can also be directed to take a photo, video or livestream of the incident by tapping on buttons at the bottom of the webpage. 

### Live Demo

The SMS link that will be sent to callers will bring them to the scdf.tech webpage. The webpage will first ask the caller to send their current GPS location data and direction of where their phone is facing for to the case file on PLACES. In the event, where further information from the caller is needed in assisting our 995 Operators to ascertain the nature of the incident, there are submission links at the bottom to allow callers to take photos and videos to upload into the system. In the submission links, the caller will be prompted to aim the incident location at the centre of their camera. This will help PLACES to narrow down the possible incident locations from the field-of-view of the caller.

Try it for yourself here -> [scdf.tech](https://scdf.tech)

### Video Demo
[Demo on YouTube](https://youtube.com)

### Future Improvements/ Extensions
#### Speech-to-Text capabilities
By tying PLACES with speech-to-text capability, additional information provided by the caller (i.e. description of what's on fire) can be cached and displayed to the 995 Operator. This would ensure that our 995 Operators will be able to understand the caller and have enough capacity to handle multiple tasks all at once. This also allows the most relevant and important information to be displayed to the operator, as callers who are closer to the incident would have a better view of the events unfolding at the incident site. 

#### Automated Information Gathering and Plotting
Instead of having a live operator issue instructions to the caller to click on the SMS link and aim at the incident using the crosshairs, this process can be automated using a virtual assistant. The resulting data can then be automatically plotted on the operator console in a concise manner. This frees up the Operator to concentrate on other tasks, and would increase the capacity and allow more callers and hence more information to be processed. 

#### Management of False Alarms
Most industrial and commercial buildings in Singapore are equipped with Decentralised Alarm Monitoring Systems, which transmits the signal from an activated fire alarm to SCDF, who then activates the relevant appliances to the incident. This improves the speed of response and serves as an early-warning system to prevent incidents from escalating to a more serious level. However, false alarms due to  malfunctions, accidents, and even environmental factors (rainy days) result in precious emergency resources being wasted, as  crews are still required to remain on scene to track down the level and zone where the alarm originated. Through PLACES, SCDF Operations Centre can directly contact the building Fire Safety Manager or other on-duty personnel through the sms link to verify through photographic or video evidence of the False Alarm, and allow crews to return to base earlier.

[Source: https://www.scdf.gov.sg/docs/default-source/scdf-library/fssd-downloads/fsm-briefing-2017---fsm-perspective-on-false-alarms-and-practical-approach-to-fire-alarm-activation.pdf]

This function can be extended to residential premises as well. False Alarms at residential premises are mainly from Members-Of-Public (MOP) who are very concerned because of loud sounds, foul smells, or white smoke in their residential area. However, these may be a result of rotting food (perhaps due to improperly closed fridge doors) or incense smoke. When a call is received from a MOP who is not the premise owner, an SMS link can be sent to the premise owner to verify if there is indeed a genuine case of emergency.
Any non-response after a short time or negative response would then trigger the Standard Operating Procedure of activating SCDF officers to respond. A positive response from the premise owner, accompanied with photographic or video evidence would confirm the false alarm and avoid the need to activate precious emergency resources.

In cases where it is not a clear false alarm, such as a burning smell without any smoke, responding SCDF officers would have to make a judgement call of breaking into the house in the event that it escalates into an actual fire. However, this may also result in unnecessary damage to property in the case of a false alarm. PLACES can be used to quickly contact the premise owner and obtain more information, such as whether there is any food on the stove, greatly improving sense-making in a highly ambiguous situation. 

### Resources Used
