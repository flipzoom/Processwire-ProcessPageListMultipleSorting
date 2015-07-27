#Admin Page Tree Multible Sorting
#####ClassName: ProcessPageListMultipleSorting

- - - 

Extend the ordinary sort of children of a template in the admin page tree in the ProcessWire CMS/CMF with multiple properties. For each template, you can define your own rule. Write each template (template-name) in a row, followed by a colon and then the additional field name for sorting. 

- - - 

**Example:** All children of the template "blog" to be sorted in descending order according to the date of creation, then descending by modification date, and then by title. Type:

```blog: -created, -modified, title```

**Pretty, huh?** Then I am pleased to receive a donation on [Flattr](https://flattr.com/submit/auto?user_id=flipzoom&url=https%3A%2F%2Fgithub.com%2FFlipZoomMedia%2FProcesswire-ProcessPageListMultipleSorting) or [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=david%2ekarich%40flipzoom%2ede&lc=DE&item_name=FlipZoom%20Media%20Inc%2e&item_number=ProcessPageListMultipleSorting&no_note=0&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHostedGuest).

- - - 

###Installation

1. Copy the files for this module to /site/modules/ProcessPageListMultipleSorting/
2. In admin: Modules > Check for new modules. 
3. Install Module "Admin Page Tree Multible Sorting".

**Alternative in ProcessWire 2.4+**  

1. Login to ProcessWire backend and go to Modules
2. Click tab "New" and enter Module Class Name: "ProcessPageListMultipleSorting"
3. Click "Download and Install"

- - - 

###Changelog

1.0.0  
* Initial release
