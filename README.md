Importing Data to a Firestore Database

Overview

Twelve years ago, Lily started the Pet Theory chain of veterinary clinics. The Pet Theory chain has expanded rapidly over the last few years. However, their old appointment scheduling system is not able to handle the increased load, so Lily is asking you to build a cloud-based system that scales better than the legacy solution.

Pet Theory's Ops team is a single person, Patrick, so they need a solution that doesn't require lots of ongoing maintenance. The team has decided to go with serverless technology.

Ruby has been hired as a consultant to help Pet Theory make the transition to serverless. After comparing serverless database options, the team decides to go with Cloud Firestore. Since Firestore is serverless, capacity doesn't have to be provisioned ahead of time which means that there is no risk of running into storage or operations limits. Firestore keeps your data in sync across client apps through real-time listeners and offers offline support for mobile and web, so a responsive app can be built that works regardless of network latency or Internet connectivity.

In this lab you will help Patrick upload Pet Theory's existing data to a Cloud Firestore database. He will work closely with Ruby to accomplish this.

Objectives

In this lab, you will learn how to:

Set up Firestore in Google Cloud.
Write database import code.
Generate a collection of customer data for testing.
Import the test customer data into Firestore.
