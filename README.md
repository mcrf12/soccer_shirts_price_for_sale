Hi all, 

I'm mcrf12 and the objective of this repository is to help anyone that would like to monitor the price of soccer shirts from the mains stores in the world.
With this code and some help from the windows task scheduler, you'll be able to receive a daily/weekly/etc mail with the prices from the shirts you are seeking, but maybe today are too expensive.

At first, only the code from Centauro's store is available, but the goal is to complete all the above over time.

- [ ] Centauro;
- [ ] Netshoes;
- [ ] FutFanatics;
- [ ] ...

How to run the code

- Mail Configuration

This code was made to send the emails from a gmail account. So, if you have one, you'll only need to follow the steps of the link below and put your info in the code.
https://www.treinaweb.com.br/blog/enviando-email-com-python-e-smtp

If you don't have a gmail account, you can always create one..
But, if you doesn't want to. The library used (smtplib) has support from another mail providers. 
So, with just a few research at stackoverflow you'll be able to adjust it.

- [Optional] Windows task scheduler to receive daily mails

Just follow the steps from the link below to create your .bat file and schedule your task.
https://datatofish.com/python-script-windows-scheduler/

[Atention for Anaconda users]
If you run your python scripts with anaconda, you'll need a few more steps described at the link below:
https://medium.com/@roddyjaques/how-to-run-anaconda-programs-with-a-bat-file-5f6dd7675508

I hope it helps you!
Best regards from Brazil!
