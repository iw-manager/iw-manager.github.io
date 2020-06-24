# Instant Widgets Editor

Is available at [https://iw-manager.github.io/](https://iw-manager.github.io/)

## Regulatory/Legal requirements
 
1. Content of Instant Widgets will be within local product, regulatory & legal responsibility
1. For every widget local product team will get local privacy & legal approval
1. From central perspective, promoting regulatory features (e.g. WebSafe) or Providing information (e.g. Corona updates) should generally be OK
1. Promotional messaging should be pre-approved by local privacy/regulatory officer
1. Any mandatory regulatory/privacy messaging should not be replaced by other messages
1. Currently there is no opt-in/out possibility provided for this feature.

## Login

To login successfully you have to use your Github login and Personal Access Token (PAT)

### How to obtain Personal Access Token (PAT)?

It is easily done in few steps:

1. Login to your Github account at [https://github.com/](https://github.com/)
1. Follow this link [https://github.com/settings/tokens/new](https://github.com/settings/tokens/new)
1. Type your Github password:
![sreenshot](https://i.snipboard.io/qAWXUy.jpg)
1. Fill the Note input (something like *Personal Access Token for Instant Widgets Editor* would do)
![sreenshot](https://i.snipboard.io/h72dj9.jpg)
1. Make sure to mark following checkboxes:
![sreenshot](https://i.snipboard.io/fPlXFd.jpg)
1. Hit **Generate Token** button
![sreenshot](https://i.snipboard.io/3Hyaxo.jpg)
1. Make sure to copy and *save* your new personal access token now. You won’t be able to see it again!
![sreenshot](https://i.snipboard.io/W1kLKV.jpg)
1. Use your PAT each time you need to login to Instant Widgets Editor
![sreenshot](https://i.snipboard.io/lCGqkU.jpg)

## Choose repository (country)

Once logged in there is a list of repositories to work with will be shown:
![screenshot](https://i.snipboard.io/aKN1HS.jpg)

**Note:** Instant Widgets Editor displays repositories that are *available* to you. In case of empty page or some repos being missing, please request access to the repositories for your Github account.

## Edit Widgets

After choosing a repository you will be redirected to Widgets editing screen.

Each environment (JIT, UAT and PROD) have their Widgets that can be added, removed, transfered and duplicated easily.

### Reordering Widgets

To change Widgets' order at an environment drag the Widget to new position.

### Editing Widgets

To edit a Widget:
1. Hover on Widget
1. Press **Edit** button that appears under the Widget
1. The editing popup will appear

#### Editing Widgets: Title & Description

Each country's supported language is presented as input field:
![screenshot](https://i.snipboard.io/s9zRbw.jpg)
![screenshot](https://i.snipboard.io/KXOLmf.jpg)

The Mobile app displays the text in accordance with the user's prefferd language.

#### Editing Widgets: Images

The image block of the editing popup is used to an image to a widget or remove the existing image. In case of removal the default color will be applied.

![screenshot](https://i.snipboard.io/Ogy1xl.jpg)

**Note:** Make sure that uploaded images meet following requirements:
Format - PNG
Minimum Width - 750px
Minimum Height - 784px
Maximum Width - 1500px
Maximum Height - 1568px

#### Editing Widgets: CTA Button Link & Text

In this block it is required to fill call-to-action texts for different languages used in a given country and paste a link the button is supposed to lead to.

![screenshot](https://i.snipboard.io/BkFdGa.jpg)

#### Editing Widgets: Audience

This dropdown is used to select an audience that will observe the Widget after publishing.

![screenshot](https://i.snipboard.io/fu5Bal.jpg)

#### Editing Widgets: Availability

In this block we set the limits in terms of dates the Widget will be available to users.
![screenshot](https://i.snipboard.io/INKgl7.jpg)

The format of dates is *day (2 digits) / month (2 digits) / year (4 digits)*
**From** is used to set start date.
**Till** is used to set end date.

#### Editing Widgets: Removing

Button **Remove Widget** is used to delete given Widget.
![screenshot](https://i.snipboard.io/F9J6r2.jpg)
To apply removing permanently make sure to publish changes for current environment (see: [https://github.com/instant-widgets-editor/instant-widgets-editor.github.io/blob/master/README.md#publishing-changes](https://github.com/instant-widgets-editor/instant-widgets-editor.github.io/blob/master/README.md#publishing-changes)).

**Note:** Each field in editing popup is required except of image, which is optional.

### Copying Widgets

To copy a Widget:
1. Hover on Widget
1. Press **Copy** button that appears under the Widget
1. The copying popup will appear

## Publishing Changes

After any changes applied the corresponding environment will display two additional buttons: **Publish** and **Revert All Changes**.
Pressing **Revert All Changes** button discards all changes made for this environment.
Pressing **Publish** button will initiate Widgets' publishing process for given environment. Notifications about the procedure could be observed. After successfull reports in the notifications it is save to reload the page.
