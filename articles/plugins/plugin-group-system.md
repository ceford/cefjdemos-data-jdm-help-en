<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_System_Group / Display title: System Group -->

## Group Description

### System - Additional Accessibility Features

This plugin adds an accessibility toolbar to your site with additional accessibility options.

![System additional accessibility features form](../../../en/images/plugins/plugin-group-system-additional-accessibility-features.png)

### System - Debug

This plugin provides debugging information. The report is shown below the main screen of the front and backend interfaces of a Joomla! installation.

#### Plugin tab

![System debug form plugin tab](../../../en/images/plugins/plugin-group-system-debug-plugin-tab.png)

- **Allowed Groups** User groups that will see the debug information when enabled.
- **Show Profiling** Whether or not to display the profiling waypoints information.
- **Show Queries** Whether or not to include the SQL query log in the debug information.
- **Show Memory Usage** Whether or not to include memory usage data in the debug information.

#### Language tab

![System debug form language tab](../../../en/images/plugins/plugin-group-system-debug-language-tab.png)

- **Show errors when parsing language files** Whether or not to display a list of language files with errors due to their not being in compliance with the Joomla! language file specification.
- **Show Language Files** Whether or not to display the language files that have been loaded to generate the page.
- **Show Language String** Whether or not to include undefined language strings in the debug information.
- **Strip First Word** Whether or not to always strip the first word in multi-word strings.
- **Strip From Start** Strips the specified words from the beginning of the language string. For multiple words separate each word with the pipe ( | ) character like so: word1|word2
- **Strip From End** Strips the specified words from the end of the language string. For multiple words separate each word with the pipe ( | ) character like so: word1|word2

#### Logging tab

![System debug form logging tab](../../../en/images/plugins/plugin-group-system-debug-logging-tab.png)

### System - Fields

The system fields plugin that is required to display the custom fields.

### System - HTTP Headers

This Plugin can set Security HTTP Headers. Please check the HTTP Header Management documentation for more details on this plugin.

![System http headers form](../../../en/images/plugins/plugin-group-system-http-headers.png)

### System - Highlight

System plugin to highlight specified terms.

### System - Job Scheduler

This plugin looks for job plugin tasks to run.

![System job scheduler form](../../../en/images/plugins/plugin-group-system-job-scheduler.png)

- **Frequency (in minutes)** Set to zero to run on every page load (for testing).
- **Webcron** Set to Yes to call as a CLI command. For more information see Writing A CLI Application.
- **Activation** Key The key to be passed in a Webcron command.

### System - Joomla! Statistics

![System joomla statistics form](../../../en/images/plugins/plugin-group-system-joomla-statistics.png)

- **Unique ID** An identifier that allows the Joomla! project to count unique installs of the plugin. This is sent with the statistics back to the server.
- **Interval (hours)** Statistics will be sent every X hours. The default is 12.
- **Mode** Select the way that you want the statistics to be sent.

### System - Joomla! Update Notification

![System joomla update notification form](../../../en/images/plugins/plugin-group-system-joomla-update-notification.png)

- **Super User Emails** A comma separated list of the email addresses which will receive the update notification emails. The addresses in the list MUST belong to existing users of your site who have the Super User privilege. If none of the listed emails belongs to Super Users, or if it's left blank, all Super Users of this site will receive the update notification email.
- **Email Language** If you choose Auto (default), the update notification email to Super Users will be in the site language at the time the plugin is triggered. By selecting a language here you are forcing the update notification emails to be sent in this specific language.

### System - Language Code

Provides the ability to change the language code in the generated HTML document to improve SEO. The fields will appear when the plugin is enabled and saved. More information at W3.org.

### System - Language Filter

![System language filter form](../../../en/images/plugins/plugin-group-system-language-filter.png)

- **Language Selection for new Visitors** Whether to choose site default language or detect browser settings automatically.
- **Automatic Language Change** This option will automatically change the content language used in the Frontend when a user site language is changed.
- **Associations** Allows item association when switching from one language to another.
- **Add Alternate Meta Tags** Add alternative meta tags for menu items with associated menu items in other languages.
- **Add x-default Meta Tag** Add x-default meta tag to improve SEO.
- **x-default Language** Choose your x-default language.
- **Remove URL Language Code** Whether to remove or not the defined URL Language Code (eg. your_domain_name/en) of your Content Language that corresponds to the default site language when SEF URL is set to *Yes*.
- **Cookie Lifetime** Language cookies can be set to expire at the end of the *Session* or after a *Year*.

### System - Log Rotation

![System log rotation form](../../../en/images/plugins/plugin-group-system-log-rotation.png)

- **Log Rotation (in days)** How often should the logs be rotated.
- **Maximum Logs** The maximum number of old logs to keep.

### System - Logout

The system logout plugin enables Joomla to redirect the user to the home page if they choose to logout while they are on a protected access page.

### System - Page Cache

This plugin enables page caching. Page caching allows the web server to save snapshots of pages and use them when serving web pages. This improves the performance of your web site and reduces the workload of the server. This plugin has the following options:

![System page cache form](../../../en/images/plugins/plugin-group-system-page-cache.png)

- **Use Browser Caching** Whether or not to use the mechanism for storing a page cache in the local browser. Default is *No*.
- **Exclude Menu Items** Select which menu items you want to exclude from caching.

### System - Privacy Consent

This plugin allows to collect the consent of your users to the site's privacy policy and to manage the consent expiration.

![System privacy consent form](../../../en/images/plugins/plugin-group-system-privacy-consent.png)

- **Short Privacy Policy** Allows you to enter a summary of your privacy policy or keep the existing one
- **Privacy Type** Choose between Article and Menu Item. Depending on choice, one or other of the two following fields will be present.
- **Privacy Article** Select or Create an Article for your privacy policy to link to your user's form.
- **Privacy Menu Item** Select or Create a Menu Item linked to an Article containing your privacy policy.
    - *Note:* Take extra care with multilingual sites. Best to ensure the Article or Menu Item occur as Associations in all languages.
- **Redirect Message** The message which will be displayed on redirectEnter your own message or keep the existing one.

![System privacy consent form expiration tab](../../../en/images/plugins/plugin-group-system-privacy-consent-expiration.png)

- **Enable** (Yes/No) Expiration is disable by default. Enable it if you want to perform checks for the expiration of privacy consents.
- **Periodic check (days)** (0 to 120 days) 30 days by default. If Expiration is enable, define the number of days to perform the check.
- **Expiration** (180 to 720 days) 360 days by default. If Expiration is enable, define the number of days when the privacy consent expires.
- **Remind** (0 to 120 days) 30 days by default. If Expiration is enable, define the number of days when a reminder should be sent before the expiration of the privacy consent.

### System - Redirect

![System redirect form](../../../en/images/plugins/plugin-group-system-redirect.png)

- **Collect URLs** This options controls the collection of URLs. This is useful to avoid unnecessary load on the database.
- **Include Domain Name in Expired URLs** Save the expired URL as absolute (include domain) or relative (exclude domain).
- **Exclude URLs** Define regular expressions or terms which should be excluded in saving.

### System - Remember Me

This plugin provides *Remember Me* functionality. This allows the website to *remember* your username and password so that you can automatically be logged in when you return to the site. This plugin has no options.

### System - SEF

This plugin adds SEF support to links in the document. It operates directly on the HTML and does not require a special tag. It has the following options:

![System sef form](../../../en/images/plugins/plugin-group-system-sef.png)

- **Site Domain** If your site can be accessed through more than one domain enter the preferred (sometimes referred to as canonical) domain here. Note: https://example.com and https://www.example.com are different domains.

### System - Session Data Purge

![System session data purge form](../../../en/images/plugins/plugin-group-system-session-data-purge.png)

- **Enable Session Data Cleanup** When enabled, this plugin wil attempt to purge expired data based on the frequency calculated by the probability and divisor.
- **Enable Session Metadata Cleanup** When enabled, this plugin wil clean optional session metadata from the database. Note that this operation will not run when the database handler is in use as that data is cleared as part of the Session Data Cleanup operation.
- **Probability** In combination with the divisor field, these two fields are used to determine the frequency of the session data cleanup operation being triggered on a request.
- **Divisor** In combination with the probability field, these two fields are used to determine the frequency of the session data cleanup operation being triggered on a request. The probability is calculated by using probability/divisor, e.g. 1/100 means there is a 1% chance that the process runs on each request.

### System - Skip To Navigation

The plugin creates a dropdown menu consisting of the links to the important places on a given web page. This makes it easier for keyboard and screen reader users to quickly jump to the desired location by choosing it from the list of options.

![System skip to navigation form](../../../en/images/plugins/plugin-group-system-skip-to-navigation.png)

### System - User Actions Log

![System user actions log form](../../../en/images/plugins/plugin-group-system-user-actions-log.png)

- **Days to delete logs after** Enter how many days logs should be kept before they are deleted. Enter 0 if you don't want to delete the logs.

### System - User Log

![System user log form](../../../en/images/plugins/plugin-group-system-user-log.png)

- **Log Usernames** This option will log the username used when an authentication fails.
