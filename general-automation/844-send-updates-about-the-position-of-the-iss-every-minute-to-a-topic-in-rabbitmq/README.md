# 844 Send Updates About The Position Of The Iss Every Minute To A Topic In Rabbitmq

This workflow retrieves the current position of the International Space Station (ISS) from an API, processes the data, and publishes it to a RabbitMQ queue for further use.

Example: A space enthusiast or a company tracking the ISS could use this workflow to automatically monitor the location of the ISS and store the data in a RabbitMQ queue. This could be useful for applications that need to display the ISS's current position, analyze its movement patterns, or integrate the data into other systems.

## What You Can Do
- Periodically retrieves the current position of the ISS from an API
- Extracts relevant data (latitude, longitude, timestamp, and name) and stores it in a RabbitMQ queue
- Runs on a cron-based schedule, ensuring the data is updated regularly

## Quick Start
1. Import this workflow to n8n
2. Configure your settings
3. Start automating!

⚠️ WARNING: Stop Building Basic Automations For Peanuts. 🚫

Here's the painful truth most won't tell you...

While 90% of builders are stuck selling $500 n8n workflows (and working way too hard)...
I'm consistently closing $6k-13k deals by doing ONE thing differently:
I combine simple automations with custom AI that takes less than a week to build.

Recent client wins:
* Turned a basic invoicing headache into a $6k project that saves my client 20 hours/week
* Built a lead generation machine for law firms - they happily paid $13k (and it runs 24/7)
* Created AI-powered SEO automation that beats funded companies (using $0 in AI costs)

Time to build each solution? Under 2 hours.

But here's what's crazy...
Most automation builders think AI is "too complex" or "too expensive" to add to their stack.
(Meanwhile, I'm charging 10x more for solutions that take the same time to build)

"Oday Bakkour" - https://seo-hunter.net/
