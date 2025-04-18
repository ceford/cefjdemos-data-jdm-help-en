<!-- Filename: Help5.x:Scheduled_Tasks / Display title: Scheduled Tasks -->

## Description

Scheduled Tasks are used to run routine site maintenance tasks as an alternative to server cron jobs. The tasks are defined in plugins in the task group. A number of task plugins are supplied and can be used as examples for creating other specialised tasks.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How To Access

Starting from the Administrator menu:

- Select **System → Manage panel → Scheduled Tasks**

The initial Scheduled Tasks list has three items.

## Screenshot

![scheduled tasks list](../../../en/images/maintenance/scheduled-tasks-list.png)

## Column Headers

Columns unique to Scheduled tasks:

- **Task Type** Tasks are created from an available list of types.
- **Last Run Date** The date and time of the last task run.
- **Next Run Date** The date and time of the next task run.
- **Test Task** A button to run the task manually.
- **Task Priority** The priority may be Low, Normal, or High. Higher priority tasks can potentially block lower priority tasks.

## Execution History

Select the button in the Toolbar to see a list of individual task executions. 

![task execution history list](../../../en/images/maintenance/scheduled-tasks-logs.png)

## Available Tasks

The following screenshot shows a list of available tasks. Some are demonstrations, some are useful.

![Scheduled Tasks Available](../../../en/images/maintenance/scheduled-tasks-types.png)

Each task has its own task related parameters that should be self-explanatory. For example, the **Site Offline** task only makes sense if the **Edit Task → Basic Fields → Execution Rule** is set to **Manual Execution**.

## Scheduled Tasks Options

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

![web cron setting](../../../en/images/maintenance/scheduled-tasks-options-lazy-scheduler.png)

- **Web Cron** Disabled is the default. Enabled requires a hash to trigger the task. Before the first save there is a message that a key is required. After save there is a field containing a Webcron link url to copy.
