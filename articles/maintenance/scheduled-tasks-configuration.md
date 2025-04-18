<!-- Filename: Help5.x:Scheduled_Tasks:_Options / Display title: Scheduled Tasks Configuration -->

## Description

Select the Options button in the Toolbar to configure scheduled tasks.

### Configure Tasks tab

![task timeout setting](../../../en/images/maintenance/scheduled-tasks-options-configure-tasks.png)

- **Task Timeout** The default is 300 seconds.

### Lazy Scheduler tab

![lazy schedule setting](../../../en/images/maintenance/scheduled-tasks-options-lazy-scheduler.png)

- **Enabled** Tasks are triggered by Site visitors.
- **Disabled** Tasks are to be triggered by an external cron job.
- **Request Interval** The default is 300 seconds.

### Web Cron tab

![web cron setting](../../../en/images/maintenance/scheduled-tasks-options-webcron.png)

- **Web Cron** Disabled is the default. Enabled requires a hash to trigger the task. Before the first save there is a message that a key is required. After save there is a field containing a Webcron link url to copy.
