# CoWin-Vaccine-Notifier
Automated Python Script to retrieve vaccine slots availability and get notified when a slot is available.
As the Covid vaccination drive is ongoing in India, the process is to register and schedule an appointment via a portal(especially for the 18-45 age group).

The catch is we don’t know when the vaccination slots are available, the option is to stock to the screen 24/7 to book a slot(not possible) but now there are few sources that send a notification when slots are available.

So in this article, we will build our own notification service which will notify us via SMS when vaccination slots are available.

Co-WIN
It is the platform through which we need to register and schedule appointments for vaccination. It provides APIs to fetch data on available slots, we will be using public API to get appointment availability based on area pin code and customize it to fetch data for the next few days.
