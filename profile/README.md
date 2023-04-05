# Drug Drone Team

> This was a project for the purposes of **HackZurich Hackathon 2018**. The DEVPOST submission is [here](https://devpost.com/software/drugdrone).

Drug delivery in emergencies has to be more accessible, direct, cheaper and faster.

## What it does
This App connects to a drone service which invokes a drone to go to the nearest drug dispenser to bring the drugs in the case of an emergency. It shows the current location of the drone to enable the user to see the remaining time untill salvation.

A use case may be an allergic reaction or an insulin defficiency in a remote area, where it is known what medication is needed directly and instantenous, without the need for a doctor.

Using this app, much money can be saved by not being spent on services like Rega, and their resources in turn get saved for other emergencies where a doctor is really needed.

## How we built it
It is an iOS App, developed with the Swift language and Firebase function as a backend.

## Challenges we ran into
We did have access to air traffic data & lists of pharmacies & drug dispenser, but no API to talk with a drone. It had to be invented : a virtual drone. Unfortunately, Firebase, the chosen host, was not as not as nice minded as hoped.

Built With
`#firebase`
`#swift`
