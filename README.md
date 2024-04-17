# YUM OR TUM

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

Detects allergies from menus and ingredient lists at the back of packaged product. Steamlines ordering at restaurants and grocery shopping.

### App Evaluation

[Evaluation of your app across the following attributes]
- **Category:** Health
- **Mobile:** Back camera, location tracking, personalization
- **Story:** Helps people feel safe eating out, decrease risk of medical emergencies, streamlines shopping and ordering process.
- **Market:** 20 million people have food allergies in the U.S., allergies can cause tummy aches to death
- **Habit:** Everytime someone goes to eat out or goes shopping (realistically a few times a week for the app to be used), Create allergy lists or warning lists
- **Scope:** I think it is doable to aim for 100% completion, A stripped-down version with just the scanning and yes/no detection is still cool

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can add allergies
* User can scan ingredient lists at the back of packages
* User can find out if that product has allergens
* User can store what dishes at a specific restaurant has allergens
* User can scan menus and find out what dishes has allergens
* User can delete allergies

**Optional Nice-to-have Stories**

* User can log in
* User can log out
* User can have a warning list of maybe allergies
* User can share allergy list to someone else (for a child to a babysitter)

### 2. Screen Archetypes

- [ ] Login Screen
* User can log into their account, which has personalized information
- [ ] Registration Screen
* User can state their name and choose their password
- [ ] My Allergies Screen
* User can create, read, update, delete allergies
- [ ] Camera Screen
* User can scan an ingredient list
* User can scan a menu, highlight a menu item, and store it as being "allergy-safe" or "contains allergies"
- [ ] Allergy List Screen
* User can see a list of potential allergens that a given food item after a scan of an ingredient list
- [ ] Map screen of restaurants with tracked dishes
* User can see a list of restaurants and the associated foods that have been identified as "allergy-safe" or "contains allergies"

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Camera Tab: If a photo is taken, it automatically gets sent to the Allergy List Screen
* My Allergies Tab: Contains personal allergies
* Restaurants Tab: Cell view of restaurants, and the associated foods that have been identified as "allergy-safe" or "contains allergies"
* Map Tab: Shows all the restaurants you have details on (User can have a good list of restaurants esp if they have a lot of bad allergies)

**Flow Navigation** (Screen to Screen)

- [ ] Camera Tab/Screen
* User can take a picture of an ingredient list
* ...
- [ ] [list second screen here]
* [list screen navigation here]
* ...

## Wireframes

[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

[This section will be completed in Unit 9]

### Models

[Add table of models]

### Networking

- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
