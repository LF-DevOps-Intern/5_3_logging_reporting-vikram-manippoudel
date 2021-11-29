<!-- sudo apt-get update  
sudo apt-get install inotify-tools  

Logging all the activities :

Reference Picture:
    tool_inotify_installation.png
    log_of_directory.png -->


> sudo apt-get install iwatch -y

Reference Picture:
    installation_iwatch.png

iwatch Version Check:
    Reference Picture:
        iwatch_version_check.png

> iwatch  -e all_events intern_monitor.txt 
    For watching log of intern_moitor.txt in foreground

    As we have to setup email to get the activity log, I have execute in foreground to show the log.

    Reference Picture:
        iwatch_monitoring.png


Followed this article at:

https://www.cyberithub.com/how-to-install-iwatch-command-on-ubuntu-20-04-lts/

Man Page of iwatch:

https://manpages.ubuntu.com/manpages/bionic/en/man1/iwatch.1.html