---
layout: post
title:  "Bluetooth Low Energy Audio"
author: Arka
categories: [ Bluetooth, Communications, UHF Radio Waves]
image: assets/images/ble2.png
last_added: true
hidden: false
---
Bluetooth Low Energy Audio, debuted at CES 2020 along with Bluetooth 5.2, promises new levels of audio fidelity with even lower bitrates than current Bluetooth audio codecs use.

With the removal of the headphone jack seeing widespread popularity among the device manufacturers, Bluetooth audio accessories started selling like hot cakes. Many different Bluetooth audio devices were introduced in the market with different Bluetooth versions and an increasing count of supported codecs. Devices supporting hi-fi codecs like AptX and AptX HD were in high demand because of their excellent audio streaming quality, but they compromised the battery life of both the streaming device and the receiving device. This was a problem which plagued the Bluetooth SIG (Special Interest Group) for many years.


## What was to be done ?
The SIG introduced many revolutionary changes with Bluetooth 5.0, like better battery life and even better audio quality, but these weren’t enough. They wanted to exploit and extend the capabilities of the **Bluetooth LE (Low Energy)** protocol. BLE (what the Low Energy protocol is often referred to as) was available since 2011, and has been used for passive connections with devices like wearables and sensors.

## Here comes Bluetooth LE Audio
![](https://github.com/monsij/insight/raw/master/assets/images/ble1.JPG)

With LE Audio, the SIG wants to add audio streaming capability to what BLE can offer us, but it requires new compression engineering. For this, Low Complexity Communication Codec (LC3) has been introduced. It claims to offer numerous improvements, like better audio quality at lower bitrates, thereby reducing power consumption.

The SIG also introduced Multi-Stream audio, with which they want to refine the audio experience when using truly wireless earbuds, like the Apple EarPods. Currently,truly wireless earbuds receive a single audio stream from the source on the primary earbud, which then hops onto the second bud, and thus might cause latency on the second bud. With Multi-Stream, the source will transmit two streams to the two earbuds at the same time, therefore reducing latency. This will also allow us to share our music with others nearby.

The SIG are also working on Broadcast Audio, which will enable streaming of the same audio to multiple devices at once, useful in places with a large gathering of people.


## When can we use it ?
With any such new technology, it does take some time till it reaches the end consumers. It is expected that this technology might start appearing on chipsets by early to mid-2020, but widespread integration into consumer devices might take a year or two. Early adoption might be possible, but it will take at least half a year according to industry estimates.

### References

[1] <a href="https://www.androidpolice.com/2020/01/07/bluetooth-le-audio/?amp" target="_blank">https://www.androidpolice.com/2020/01/07/bluetooth-le-audio/</a>
