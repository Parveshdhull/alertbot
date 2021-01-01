# alertbot - Organized Reminder App

Simple program to create reminders and send desktop notifications or slack alerts.

## Features
- Very easy to create new reminders
- Create recurring reminders - daily, monthly, yearly
- Saves failed or missed reminders (Ex. PC Turned Off, No Internet) - And sends them later.
- Categories reminders in different sections
- Create birthday alerts

## Prerequisite:
pip install py-notifier

## Configuration (Optional)
* **Configure Slack**
	You can skip this step if you only want to receive desktop notifications.
https://github.com/Parveshdhull/slackbot
	

## Usage

	alertbot -r reminders_file -m slack

- -r : Reminders File Location
- -m : Mode (slack, desktop, both)

## Reminders File

An example reminders file is also included. 

Syntax :- 

​	Date(yyyy-mm-dd) "Message" TIME(HH:MM) 

Note - Here Quotes(") are required

## Example:

#### Alert Once - Full date is required

```yyyy-mm-dd "message" hh:mm```

#### Daily - Only Time is required

```"message" hh:mm```

#### Monthly - Only Date is required

```dd "message" hh:mm```

#### Yearly - Date and Month is required

```mm-dd "message" hh:mm```

## Cron
Create cron entry interval, as per your requirement
```* * * * * alertbot -r reminders -m slack```


## Liked my work?
<a href="https://www.buymeacoffee.com/parveshmonu" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## Websites
https://github.com/Parveshdhull
<br />https://twitter.com/ParveshMonu
<br />https://youtube.com/right2trick
