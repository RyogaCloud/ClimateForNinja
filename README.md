# ClimateForNinja
[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)


## Contents

1. [Short description](#short-description)
1. [Demo video](#demo-video)
1. [The architecture](#the-architecture)
1. [Long description](#long-description)
1. [Solution roadmap](#solution-roadmap)
1. [Getting started](#getting-started)
1. [Contributing](#contributing)
1. [Authors](#authors)


## Short description

A tool for developers confronting climate change


## Demo video
[![Watch the video](https://github.com/RyogaTakao/ClimateForNinja/blob/futureSever/fig/Video_Image.png)](https://youtu.be/8KhJ5azM-5g)


## The architecture
![Architecture](https://github.com/RyogaTakao/ClimateForNinja/blob/futureSever/fig/Architecture.png)

1. Get room temperature with Raspberry Pi and temperature sensor.
1. Format the acquired data with Node-RED in Raspberry Pi and send the data to IBM Watson IoT Platform.
1. Load the data posted to IBM Watson IoT Platform with Node-RED on IBM Cloud.
1. Store the loaded data and outdoor temperature retrieved from The Weather Company API in cloudant with Node-RED on IBM Cloud.
1. Format the data stored in cloudant into JSON format.
You can get the JSON by sending an Http/Get request.
1. Send an Http/Get request to the above to get the data.
Display a graph of the data and a JSON string as a web application


## Long description

According to IBM global study conducted by Morning Consult , Eight out of  ten respondents agree with the idea that “people want to do something to help combat climate change, but don't know where to start.”
What can we do to support for them? To solve this problem, we made API, essential tool around developers, which turns the abstract word, ‘Climate Change’ into more concrete one for them to use.
We focused on  ‘Air conditioner’, because we’ve faced and will face environmental problems such as overusing fossil fuels causing climate change. For instance, International Energy Agency states that around 2/3 of the world’s households could have an air conditioner by 2050. In addition, energy demand for space cooling will more than triple by 2050. Thus, we address to Air Conditioner, one of the most familiar household appliances in our lives. 
Climate for NINJA measures temperature while operating air conditioner and allows users to visualize the fluctuation of room temperature and outside temperature at the same time.
Developers can create following services with our API :
- service that urges users to turn off the air conditioner when there is little difference between measured room temperature and outside temperature
- When internal temperature at home or stopped car with the elderly or small child expects to get higher considering outside temperature, services that notify their parents or carers and automatically turn on the air conditioner

Like these, this solution brings many positive outcomes. The more developers make use of this solution, the more customer demand we can responded to. Also, we utilized Node-RED in developing API, which allows us to introduce it to many companies at low cost due to its ease of distribution.  
API has more potential than a single product or service because it can be transformed to anything by benefiting from excellent developers.


## Solution roadmap



## Getting started



## Contributing



## Authors
- [RyogaTakao](https://github.com/RyogaTakao)(Back-end engineer)
- [YoshiharuSenna](https://github.com/YoshiharuSenna)(Front-end engineer)
- [TatsuyaOkazaki324](https://github.com/TatsuyaOkazaki324)(Embedded engineer)
- (planner)