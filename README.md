# UX--UI of the Blessed solution
Our submission for the UX / UI competition


---
Blessed UX Solution
A comprehensive showcase of our UX solution
---

# Blessed UX Solution

Welcome to the presentation page of our innovative UX solution "Blessed". This page highlights our unique approaches and the results we've achieved.

## Table of Contents
1. [Introduction](#introduction)
2. [Showreel](#showreel)
3. [UX Challenges](#Our-UX-Challenges)
4. [Our Solution](#our-solution)
5. [Image Gallery](#image-gallery)
6. [Animation](#animation)

## Introduction

Our mission is to add a user experience (UX) that has the capability to onboard masses. With "Blessed", we've crafted a solution that is intuitive, effective, and visually captivating. We considered the challenges users face when waiting in virtual queues for oversubscribed events. Our goal was to make this process more engaging and enjoyable while ensuring a fair and transparent distribution model for such events. Our solution strikes for the perfect balance, transforming waiting times into enjoyable experiences while making ticketing fair und transparent. 

## Stylescape

Here is our Stylescape that showcases the key features and highlights of our UX solution as giving you a feeling how the UX plays in harmony with the branding

![Showreel](path/to/showreel.gif)

## Our UX Challenges

We face various UX challenges.
On the one hand we needed to think about the ticketing problem.

How can we make the frustrating process of buying into an oversubcribed event enyoable again?
How can we activate our future event attendees?
How can the process be fairer?

On the other hand we needed to think about the infrasstructure we use.

How can we use Gelato.networks RaaS, their middleware as VRF, relayer and their thirdparty integrations as Thirdweb to be as onboarding friendly as a new infrastructure need to be to get masses to use them and try to minimilize technical restrictions for normies.

How should a user know kow how to create a wallet?
How can a user know that there might be a fee to pay for clicking a button aka doing some actioins? Where should the user get the fee token from?
How can a normie get all the technical barriers of the existing infastructure landscape?

## Problem Statement and Ideation Process

The goal of our project is to create a seamless experience for users transitioning between exploring event background information and purchasing tickets. This objective serves as a foundational framework to guide all subsequent decisions:

```
“Make switching between exploring the event background information and purchasing a ticket feel natural.”
```
This guiding principle has led us to explore various ideas aimed at entertaining and engaging the user, such as:   
During Waiting Periods:  
Entertainment and Information Slider: An interactive window featuring an entertainment and information slider to keep users engaged while they wait.  
“Take a Break” Switch: A switch that transforms the slider content into a "Back to Lottery" view, supported by a vertical switch flip animation for a smooth transition between the slider and lottery areas.  
Cooldown Phase Countdown: A countdown timer with color coding in "BLESSED Chill Blue" to indicate cooldown phases, providing users with a clear visual cue for breaks.  
Visualizing the Four Main Phases:  
We employ a running down time metaphor in the bars representing the four phases of our product's main functionality.  
Active and Remaining Time: Represented by the active color "Harmony Green."  
Passed Time: Indicated by turning the bar grey in "Whispering Fog."  
These features are designed to create an intuitive and engaging user experience, ensuring that every aspect of the interface aligns with our overarching goal.  



Technical approach:
- Step I - Wallet creation by Thirdweb - means any user can create a wallet in the back by using his mail, google account and also Apple ID. Any crypto native can sign in with tehri existing wallet. We did not design the Login UI as we used the free for the hackathon UI from Thirdweb for that. 
- Step II - Paying Gas to do any form of transaction is the next UX challenge to onboard non crypto natives. Here we used Gelatos Relayer option and Thirdwebs account abstraction. 
- Step III - Bundling transactions - as we create various contracts per event they needed to be deployed by the creator of the event. We used OpenZepplins Clone function to bundle these into a single transaction, that is executed now when the event creator clicks the create event button. 

### Main Functionalities

We have an "Enroll" area docked to the event detail pages, which opens as soon as the user initiates the enrollment process. 
Within the opened "Enroll" area, the user will see the main ticket purchasing section, which can be collapsed by clicking an arrow icon.

When closed, this area displays information about the remaining time of the lottery or auction phase. 
We have four phases: Lottery 1, Lottery 2, Auction 1, and Auction 2. Following these phases, there is a Marketplace where users can resell their tickets.

The "Enroll" area is divided into two parts: 
Left Side: The deposit and cart area.
Right Side: Occupying more than two-thirds of the space, this is the main part of the interactive window. It contains an interactive timeline showing the duration of each phase. At the top of this section, there is information about the entire ticket purchasing process for the event, including its end time.

Below the phases timeline, there are boxes with information and interactions specific to each phase. For example, in Lottery 2, users can add more money to generate numbers, increasing their chances of winning. To make this action more engaging and exciting, the highlight color orange is used for the button.

Notifications appear on the right sidebar within the interactive window area. These notifications inform the user about:
Cooldown Phase Start: Color-coded as Chill Blue.
Boost Phase Activation: Color-coded as Vibrant Orange.
Friendly Reminders: To generate a new number, also in Vibrant Orange.
Win Notification: Color-coded as Mystic Berry, accompanied by a micro animation with confetti, drawing attention to the cart/deposit/mint area on the left.


Labeling and terminology  
For the Phases we are thinking about making them more engaging and more human through names like ...

** Link for Notion and see contnet there** 

### Design

A text block about the design and the unique aspects of our solution.


## Image Gallery

A selection of images that illustrate our solution:

![Image 1](path/to/image1.jpg)
*Description of Image 1*

![Image 2](path/to/image2.jpg)
*Description of Image 2*

## Animation

An animation that demonstrates the functionality of our solution:

![Animation](path/to/animation.gif)


---

_Color Coding:_

- **Background Color:** #FFFFFF
- **Primary Color:** #3498db
- **Secondary Color:** #2ecc71
- **Text Color:** #333333

