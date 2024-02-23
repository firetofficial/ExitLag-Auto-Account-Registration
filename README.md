<<<<<<< HEAD
> **Warning**
> Please be advised that usage of this tool is entirely at your own risk. I assumes no responsibility for any adverse consequences that may arise from its use, and users are encouraged to exercise caution and exercise their own judgment in utilizing this tool.

# ExitLag Auto Signup

Automatically create ExitLag accounts using temporary email addresses.

## Technologies Used

- Python
- Selenium
- Requests-HTML

## How it works

The process begins by utilizing the [Mail.GW](https://mail.gw/) service to obtain a temporary email address. This email address is then utilized to sign up for an [ExitLag](https://exitlag.com) account. Subsequently, another request is made to [Mail.GW](https://mail.gw/) to retrieve the email confirmation link. Upon activation of the account, the user is able to log in to the ExitLag application and benefit from its functionality.


> **Warning**
> It is important to note that excessive usage of this tool may result in rate limiting by the API or, in severe cases, IP blocking. To avoid these potential consequences, it is recommended to limit the number of usage. (Maybe 5 times every 10 minutes?)

### Prerequisites

- Python installed
- Google Chrome browser

## Installation / Usage

First, clone this repository:
```shell
git clone https://github.com/qing762/exitLag-auto-signup/
```
Install [Google Chrome](https://google.com/chrome/) (IMPORTANT!)
```shell
INSTALL HERE: https://google.com/chrome/
```

Install the necessary dependencies:
```shell
pip install -r requirements.txt
```

Next, run the Python file:
```shell
python main.py
```

And you're all set! Follow the instructions while interacting with the Python file.

## Known issues
[Here are a list of known issues and on how you can fix it](https://github.com/qing762/exitlag-auto-signup/discussions/4)

## Contributing

Contributions are always welcome!

To contribute, fork this repository and improve it. After that, press the contribute button.


## Feedback / Issues / Request for takedown

If you have any feedback or issues running the code, please reach out to me at [Discord/qing762](https://discord.com/users/635765555277725696)


=======
# ExitLag-Auto-Account-Registration
This repository contains a Python tool that automates the process of creating an ExitLag account using a temporary email address. It leverages Selenium for web automation and interacts with the Mail.GW service to fetch temporary email addresses.
>>>>>>> 4a63ad52669b3bcdcb7f84de5dc478fe0ca7cff4
