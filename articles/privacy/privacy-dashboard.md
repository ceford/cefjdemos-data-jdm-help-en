<!-- Filename: Help4.x:Privacy_Dashboard / Display title: Privacy Dashboard -->

## Description

This screen lists User Privacy Request Type, Status and Number of
requests.

### Tutorials

- [Privacy Outline - Content and Workflow](https://docs.joomla.org/Help4.x:Components_Privacy_Outline/en)
- [The Privacy Tool Suite](https://docs.joomla.org/J3.x:Privacy/en)
  (Detailed Tutorial from Joomla 3)
- [Information Request Workflow](https://docs.joomla.org/J3.x:Information_Request_Workflow_in_Privacy_Component/en)
  (Detailed Tutorial from Joomla 3)

## How to access

- Select **Users → Privacy Dashboard icon** from the Administrator menu.

## Screenshot

![privacy dashboard](../../../en/images/privacy/privacy-dashboard.png)

## Dashboard Panels

### Privacy Status

- **Published Privacy Policy** Whether a Privacy Policy is available. Navigate
  to *Plugins → System - Privacy Consent* and select your Privacy Article.
  Once published, you can edit your Privacy Policy article from this screen.
- **Published Request Form Menu Item**  Whether the Menu Item (which allows
  users to send requests) is published or unpublished. To create it, navigate
  to your Menu → Add New Menu Item → Menu Item Type: Create Request. Once
  published, you can edit your menu item from this screen.
- **Outstanding Urgent Requests** Number of urgent requests which are
  older than the number of days set in the Component Options (from 10 to
  29 days).
- **Mail Sending Enabled**
- **Database connection encryption**

### Privacy Requests

- **Request Type** Displays the two different types of request
  - Export: when a user has sent a request for an export of their data
  - Remove: when a user has sent a request to be removed.
- **Status** Displays the status of the request
  - Invalid: a Super user has invalidated the request
  - Pending: when a user has sent a request but hasn't confirmed their
    request yet. Users have 2 ways to confirm: by visiting the URL
    mentioned in the email sent to the user or by copying the token from
    the email and paste it into the form in the given URL. The token is
    valid for 24 hours.
  - Confirmed: the user has confirmed their request.
  - Completed: a Super user has completed the request
- **\# of requests** Displays the number of requests for each type. This
  block displays also the total number of requests and the number of
  active requests

## Tips

- Click on a Request Type to view the requests.
