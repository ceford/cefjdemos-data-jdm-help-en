<!-- Filename: Help5.x:Scheduled_Tasks:_Edit / Display title: Edit Task -->

## Description

Each task has its own task related parameters located in the *New or Edit Task* tab of the Edit Task form. The fields should be self-explanatory. The additional form tabs are common to all of the tasks.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How To Access

- Select **System → Manage → Scheduled Tasks** and select the *+ New* button in the Toolbar. Or...
- Select **System → Manage → Scheduled Tasks** and select a Task from the list.

## Joomla! Update Notification

This task periodically checks for the availability of new Joomla! versions. When one is found it will send you an email, reminding you to update. You can customise the email at System → Mail Templates.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-joomla-update-notofication.png)

### Advanced Tab

![joomla update notification advanced tab parameters](../../../en/images/maintenance/scheduled-tasks-types-advanced-tab.png)

### Execution History Tab

![joomla update notification execution history tab parameters](../../../en/images/maintenance/scheduled-tasks-types-exec-history-tab.png)

### Details Tab

![joomla update notification details tab parameters](../../../en/images/maintenance/scheduled-tasks-types-details-tab.png)

## Delete Action Logs

Delete Action logs after specified days.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-delete-action-logs.png)

## Expiration of Privacy Consents

Manage the expiration of privacy consents.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-privacy-consent.png)

## GET Request

Make GET requests to a server. Supports a custom timeout and authorization headers.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-get-request.png)

## Global Checkin

Check in checked out items.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-global-check-in.png)

## Image Size Check

Check images, resize if larger than allowed. Attention: The original file will be overwritten! 

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-image-size-check.png)

- **Directory** The Directory of the image to check, perhaps sampledata, banners or headers.

- ** Dimension** The dimension of the image to check, Width and Height.

## Rotate Logs

Periodically rotates log files.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-rotate-logs.png)

## Session Data Purge

Task Plugin that purges expired data and metadata depending on the session handler set in Global Configuration.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-session-data-purge.png)

## Set Site Offline

Sets site status to offline on each run.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-set-site-offline.png)

## Set Site Online

Sets site status to online on each run.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-set-site-online.png)

## Toggle Offline

Toggles the site's status on each run.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-types-toggle-offline.png)

