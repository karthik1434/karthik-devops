# * * * * * command or path to a script

# *         -it minits 0 to 59
#   *       -it is howers 0 to 23
#     *     -it is days 1 to 31
#       *   -it is months 1 to 12
#         * -it is day of week 0 to 6


systemctl status httpd #how to check servece running ststus

system deman

systemd is a system and service manager for linux operating system
its is desined to manage the core componants of a system, and control 
the startup process and supervise system process after boot.
systemd provide functionalities like stoping start up process, 
manage services mounting and logging system events.
its ps no is 1

ps -aux :- to view systemd proces
ps -aux |grep "service name"
sudo systemctl list-units :- to list services
sudo systemctl list-units -t service :- to list services
sudo systemctl list-units-files |grep "ngnix" :- to list services



systemctl :- 
 is a command-line utility in Linux systems that is used to control the systemd system and service manager. It is a powerful tool that allows users to manage services, view system states, control the systemd unit files, and perform various system and service-related tasks.

systemctl start <servicename>
systemctl stop <servicename>
systemctl restart <servicename>
systemctl enable <servicename>
systemctl disable <servicename>
systemctl version
systemctl | grep "service name"

journalctl :-
is a command that allow user to query and view logs collected by the systemd journal

journalctl: Shows the entire journal from the current boot session.
journalctl -u service_name: Displays logs for a specific service.
journalctl --since "2023-01-01" --until "2023-12-31": Shows logs within a 
journalctl -p err: Filters logs to show only messages with "error" priority or higher.
journalctl _SYSTEMD_UNIT=httpd.service: Displays logs for a specific systemd unit (in this case, 'httpd.service').
journalctl -k: Shows kernel messages.
journalctl -f: Displays live, continuously updating logs.

hostnamectl:-
localctl:-
timedatectl:-
system-cgls:-
systemadm:-

change port no of service :- vi/etc/ssh/sshd-config

cgroups & name spaces

