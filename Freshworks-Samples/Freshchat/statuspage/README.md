# Statuspage Sample App for Freshchat

### Description:

Shows the component-level status of the Statuspage that we intend to monitor from Freshchat

### Screenshots:

_[Screenshots that are not too big/small. Gifs are best. Let's just stick to 3 screenshots at the max]_

Features demonstrated | Notes
-------------------- | ------
 _Feature Name_ | _How the app is using it_

### Prerequisites

1. Make sure you have the development environment setup with the latest version of FDK. If you are starting from scratch, You can have a look at the  [quick start](https://developers.freshchat.com/v2/docs/quick-start/) mentioned here. Skip this step if you already have the FDK installed

2. Create a test Statuspage account and provide the required details for the installation parameters. Use `config/iparam_test_data.json` for [local testing](https://developers.freshchat.com/v2/docs/quick-start/#test_your_app).

### Procedure to run the app:
1. Run the app locally using the [`fdk run`](https://developers.freshchat.com/v2/docs/freshworks-cli/#run) command

2. You'll notice the statuspage app in the sidebar.
It is refreshed based on the poll frequency to obtain the status
![Screenshot](app/demo.png)

3. You can automate/send [partial-outage/downtime emails](https://help.statuspage.io/help/getting-started-with-email-automation) to the concerned status page and the respective status of the component would reflect in the sidebar
