## Gates

The gates are designed to redirect traffic from other captcha services to imagetyperz.com

Currently, we've integrated the following services:

- 2captcha.com
- deathbycaptcha.com
- anti-captcha.com

### Usage

In order to use the gate, check the `scripts` folder. Inside it, you'll find a batch program / file for each service.
Execute the file with the name you want to redirect.

The program will write a redirection rule in your Windows hosts file. In order to disable a gate once activated, remove the entry added by the bat file from: `%SystemRoot%\System32\drivers\etc\hosts`

### License
MIT