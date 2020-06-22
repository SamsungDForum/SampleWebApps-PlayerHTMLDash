# Dash.js Player

This application demonstrates the usage of **Dash.js** player.

Using **Dash.js** user is able to play streams using HTML5 `video` tag.


## How to use the application

Use TV remote controller to navigate. 

Using **Next** and **Previous** buttons user can change streamed content.

There are **Play** / **Pause**, **Stop**, **Fast forward**, **Rewind** and **Full screen** buttons to control playback.


## Supported platforms

2017 and newer


### Prerequisites

To use **Dash.js** Player, 

``<script type="text/javascript" src="http://cdn.dashjs.org/latest/dash.all.min.js"></script>``

should be loaded in `index.html`.

### File structure

```
PlayerHTMLDash/ - PlayerHTMLDash sample app root folder
│
├── assets/ - resources used by this app
│   │
│   ├── dash.all.min.js - library containing DASH player
│   └── JosefinSans-Light.ttf - font used in application
│
├── css/ - styles used in the application
│   │
│   ├── main.css - styles specific for the application
│   └── style.css - style for application's template
│
├── js/ - scripts used in the application
│   │
│   ├── init.js - script that runs before any other for setup purpose
│   ├── keyhandler.js - module responsible for handling keydown events
│   ├── logger.js - module allowing user to register logger instances
│   ├── main.js - main application script
│   ├── navigation.js - module responsible for handling in-app focus and navigation
│   └── utils.js - module with useful tools used through application
│
├── CHANGELOG.md - changes for each version of application
├── config.xml - application's configuration file
├── icon.png - application's icon
├── index.html - main document
└── README.md - this file
```

## Other resources

*  **Dash.js github page**  
  https://github.com/Dash-Industry-Forum/dash.js


## Copyright and License

**Copyright 2019 Samsung Electronics, Inc.**

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.


**Dash.js license**

Dash.js is licensed under BSD-3 license:
https://github.com/Dash-Industry-Forum/dash.js/blob/development/LICENSE.md
