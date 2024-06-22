<!-- Filename: Help4.x:Privacy_Dashboard / Display title: Privacy Dashboard -->

## Description

This screen lists User Privacy Request Type, Status and Number of
requests.

### Tutorials
- Privacy Outline - Content and
  Workflow
- The Privacy Tool
  Suite
    (Detailed Tutorial from Joomla 3)
- Information Request
  Workflow
    (Detailed Tutorial from Joomla 3)

## How to access

- Select **Users → Privacy Dashboard icon** from the Administrator menu.

## Screenshot

<img
src="https://docs.joomla.org/images/c/c3/Help-4x-component-privacy-dashboard-en.png"
decoding="async" data-file-width="800" data-file-height="472"
width="800" height="472"
alt="privacy dashboard screenshot" />

## Dashboard Panels

### Privacy Requests

- *Request Type.* Displays the two different types of request
  - Export: when a user has sent a request for an export of their data
  - Remove: when a user has sent a request to be removed.
- *Status.* Displays the status of the request
  - Invalid: a Super user has invalidated the request
  - Pending: when a user has sent a request but hasn't confirmed their
    request yet. Users have 2 ways to confirm: by visiting the URL
    mentioned in the email sent to the user or by copying the token from
    the email and paste it into the form in the given URL. The token is
    valid for 24 hours.
  - Confirmed: the user has confirmed their request.
  - Completed: a Super user has completed the request
- *\# of requests.* Displays the number of requests for each typeThis
  block displays also the total number of requests and the number of
  active requests

### Privacy Status

- *Privacy Policy Published.*(Published/Unpublished) Whether the Privacy
  Policy is published or unpublished. Navigate to Plugins → System -
  Privacy Consent, and select your Privacy Article. Once published, you
  can edit your Privacy Policy article from this screen.
- *Request Form Menu Item Published.* (Published/Unpublished) Whether
  the Menu Item (which allows users to send requests) is published or
  unpublished. To create it, navigate to your Menu → Add New Menu
  Item → Menu Item Type: Create Request. Once published, you can
  edit your menu item from this screen.
- *Outstanding Urgent Requests.* Number of urgent requests which are
  older than the number of days set in the Component Options (from 10 to
  29 days).

## Quick Tips

- Click on a Request Type to view the requests.
