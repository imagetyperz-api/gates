## Gates

Deathbycaptcha,anti-captcha and 2captcha api support for integration with any software

### Usage

In order to use the gate, check the `scripts` folder. Inside it, you'll find a batch program / file for each service.
Execute the file with the name you want to redirect.

The program will write a redirection rule in your Windows hosts file. In order to disable a gate once activated, remove the entry added by the bat file from: `%SystemRoot%\System32\drivers\etc\hosts`

For more details about the hosts file check [this](https://www.howtogeek.com/howto/27350/beginner-geek-how-to-edit-your-hosts-file/) link

### License
MIT
