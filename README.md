# Notify

## Authors
* Nikhilesh Vegesna
* Salil Vanvari

## Purpose
* Raw Text: Enable groups to communicate effectively without the side chatting associated with large group texts. 

## Features
* Customozable Notifications
* Secure Groups with admin controls
* Uncluttered messaging

## Control Flow
Users will be shown a splash screen with our apps name and logo while background app loads and pulls data about your groups. The groups will then be displayed in a collection view and users can tap a group and quickly jump into notifications from group/create a new notificaiton for the group. You may also create a new notification or group from the homepage where all groups are displayed. Furthermore you may search for existing groups and add upon admin approval. 

## Implementation
### Model
* Groups.swift
* Notification.swift

### View
* manageGroupView
* homePageView
* createNewNotification

### Controller
* manageGroupViewController
* homePageController
* createNewNotificationController
