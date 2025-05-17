# 845 Receive Messages From A Queue Via Rabbitmq And Send An Sms

This workflow monitors a RabbitMQ queue, checks if the value of the "temp" parameter exceeds 50, and sends an alert via Vonage if the condition is met.

Example: This workflow could be used to monitor a temperature sensor that sends data to a RabbitMQ queue. If the temperature exceeds a certain threshold (in this case, 50 degrees), the workflow will send an alert to a designated phone number, allowing the user to take immediate action.

## What You Can Do
- Triggers on new messages in a RabbitMQ queue
- Checks the value of a specific parameter ("temp") against a predefined threshold
- Sends an alert via Vonage if the condition is met
- Provides a "no-op" node for cases where the condition is not met

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
