<!--
{
  "source": "https://docs.joomla.org/Help5.x:Scheduled_Tasks:_Edit",
  "title": "Edit Task ",
  "description": "", 
  "author": ""
}
-->

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

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/01-joomla-update-notofication.png)

### Advanced Tab

![joomla update notification advanced tab parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/02-advanced-tab.png)

### Execution History Tab

![joomla update notification execution history tab parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/03-exec-history-tab.png)

### Details Tab

![joomla update notification details tab parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/04-details-tab.png)

## Delete Action Logs

Delete Action logs after specified days.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/05-delete-action-logs.png)

## Expiration of Privacy Consents

Manage the expiration of privacy consents.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/06-privacy-consent.png)

## GET Request

Make GET requests to a server. Supports a custom timeout and authorization headers.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/07-get-request.png)

## Global Checkin

Check in checked out items.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/08-global-check-in.png)

## Image Size Check

Check images, resize if larger than allowed. Attention: The original file will be overwritten! 

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/09-image-size-check.png)

- **Directory** The Directory of the image to check, perhaps sampledata, banners or headers.

- ** Dimension** The dimension of the image to check, Width and Height.

## Rotate Logs

Periodically rotates log files.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/10-rotate-logs.png)

## Session Data Purge

Task Plugin that purges expired data and metadata depending on the session handler set in Global Configuration.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/11-session-data-purge.png)

## Set Site Offline

Sets site status to offline on each run.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/12-set-site-offline.png)

## Set Site Online

Sets site status to online on each run.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/13-set-site-online.png)

## Toggle Offline

Toggles the site's status on each run.

![joomla update notification parameters](../../../en/images/maintenance/scheduled-tasks-edit-task/14-toggle-offline.png)

