---
layout: post
title:  "Bluetooth Low Energy Audio"
author: Arka
categories: [ Bluetooth, Communications, UHF Radio Waves]
image: assets/images/ble2.png
last_added: true
hidden: false
---
Bluetooth Low Energy Audio, debuted at the CES 2020 along with Bluetooth 5.2,
promises new levels of audio fidelity with even lower bitrates that the current
Bluetooth audio codecs use.

With the removal of the headphone jack seeing widespread popularity among the
device manufacturers, Bluetooth audio accessories started selling like hot cakes.
Many different Bluetooth audio devices were introduced in the market with
different Bluetooth versions and an increasing count of supported codecs. Devices
supporting hi-fi codecs like AptX and AptX HD were in high demand because of
their excellent audio streaming quality, but they compromised the battery life of
both the streaming device and the receiving device. This was a problem which
plagued the Bluetooth SIG (Special Interest Group) for many years.

## What was to be done ?
The SIG introduced many revolutionary changes with Bluetooth 5.0, like better
battery life and even better audio quality, but they weren’t enough. They
wanted to exploit and extend the capabilities of the Bluetooth LE (Low Energy)
protocol. **BLE** (what is the Low Energy protocol often referred to as) was available since
2011, and has been used for passive connections with devices like wearables and
sensors.

## Here comes Bluetooth LE Audio
![](https://github.com/monsij/insight/raw/master/assets/images/ble1.JPG)

With LE Audio, the SIG wants to add audio streaming to what BLE can offer us, but
it requires new compression engineering. For this, Low Complexity
Communication Codec (LC3) has been introduced. It claims to offer many
improvements, like better audio quality at lower bitrates, thereby reducing power
consumption.

The SIG also introduced Multi-Stream audio, with which they want to refine the
audio experience when using truly wireless earbuds, like the Apple EarPods.
Currently, they receive a single audio stream from the source on the primary
earbud, which then hops onto the second bud, and might cause latency on the
second device. With Multi-Stream, the source will transmit two streams to the
two earbuds at the same time, therefore reducing latency. This will also allow us
to share our music with others nearby.

They are also working on Broadcast Audio, which will stream the same audio to
multiple devices at once, useful in places with a large gathering of people.

## When can we use it ?
With any such new technology, it will take some time till it reaches the end
consumers. They might start appearing on chipsets by early to mid-2020, but
widespread integration into consumer devices might take more than a year or two.
Early adoption might be possible, but it will take at least half a year.
