Data for the paper "A Machine Learning Framework for Harvesting and Harmonizing Cultural and Touristic Data", published in the "Information" Journal/MDPI

Data from all harvested sources. The schema of the files are as follows:

## ta-venues.csv:
* name_gr: name of the venue in the Greek language
* name_en: name of the venue in the English language
* categories: the categories in which the venue belongs to
* address: the physical address of the venue
* phone: the phone number of the venue
* url: the URL of the venue's site
* longitude: the longitude of the venue
* latitude: the latitude of the venue


## fb-venues.csv
* name: name of the venue, in the lannguage entered by the owners/administrators
* days_hours_open: days and hours during which the venue is open
* site: the URL of the venue's site
* phone: the phone number of the venue
* email: the email address of the venue
* address: the physical address of the venue
* category: the category in which the venue belongs to
* latitude: the latitude of the venue
* longitude: the longitude of the venue

## odysseus-venues.csv
* grTitle: name of the venue in the Greek language
* enTitle: name of the venue in the English language
* longitude: the longitude of the venue
* latitude: the latitude of the venue

## homogenized-venues.csv
* title: name of the venue in the Greek language
* title_en: name of the venue in the English language
* website: the URL of the venue's site (if sources list different URLs, only one is listed here)
* phone: the phone number of the venue 
* address: the physical address of the venue in the Greek language
* address_en: the physical address of the venue in the English language
* email: the email address of the venue
* coords: the coordinates of the venue

