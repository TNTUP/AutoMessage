Unofficial fork of AutoMessage by ELCHILEN0. 

WARNING YOU HAVE BEEN WARNED, THIS FORK BREAKS THE JSON CAPABILITY BECAUSE I HAVE ADDED SUFFIXES/PREFIXES!!!!

This fork readds the removed suffixes/prefixes which ELCHILEN0 removed (probably due to JSON or idk why...)

Though, some changes in your config is needed...

Before, in your config.yml you can see this:

```yml
message-lists:
  regular:
    enabled: true
    interval: 45
    expiry: -1
    random: false
    prefix: '[&bPrefix&r] \n'
    suffix: ' [&4Suffix&r] \n'
    messages:
    - '&1First&r message \nin the default list!'
    - '&2Second&r message \nin the default list!'
    - '&3Third&r message \nin the default list!'
    - These messages will be displayed to users with \nautomessage.receive.regular!
```
Result: ![Result](https://i.qcfb.ca/20170526010833.png)

...and you want new lines at prefixes/suffixes but it doesn't work! HELP! Don't worry, I have found a workaround, change those ' ' to " " like this:

```yml
    prefix: "[&bPrefix&r] \n"
    suffix: " [&4Suffix&r] \n"
```
Result: ![Result2](https://i.qcfb.ca/20170526010706.png)
...and poof it works!!!

Although I'm quite a oldschool guy. I know JSON is way prettier than regular but I was sad when the dev removed the support of prefix/suffixes. I have readded them back (Sorry, looked at the commit when you have removed it, forgive me :'(

but beware, don't use it if you love JSON. It breaks it and I don't care fixing it for my server. But for others, better asking to ELCHILEN0 instead.
