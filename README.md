# dns-exfil

A program to exfiltrate files from computers using the DNS.

## Background

Years ago, a government auditor insisted that keystroke loggers had to run as root, otherwise they would not function properly. So, I wrote a keystroke logger that ran as a normal user. He wasn't amused. 

Some time later, the same auditor was back again. This time, he was adamant that I would not be able to copy files from his 'secure' and 'complaint' enclave. So, I wrote this program to, again, prove otherwise.This time, he was even less amused.

While I no longer publish the keystroke logger source code (it was abused too much), I wanted to make this old code public. I wrote this quickly to prove a technical truth to a bureaucrat, so please forgive the code quality. It works, of course, but could use some polish.

## Notes

I used BIND when I initially wrote this. However, any authoritative DNS server would do. Today, I use coredns as it's easier to setup and more secure.
