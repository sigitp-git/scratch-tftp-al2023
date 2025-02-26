### scratch-tftp-al2023

RFC 7440 modified tftpd-hpa server

```
[ec2-user@ip-172-31-69-236 ~]$ wget https://github.com/sigitp-git/scratch-tftp-al2023/raw/refs/heads/main/scratch-tftp.zip

[ec2-user@ip-172-31-69-236 ~]$ unzip scratch-tftp.zip
Archive:  scratch-tftp.zip

[ec2-user@ip-172-31-69-236 scratch-tftp]$ sudo yum localinstall tftp-server-5.2-43.amzn2023.aarch64.rpm
Last metadata expiration check: 5:58:58 ago on Tue Feb 25 22:08:18 2025.
Dependencies resolved.
=========================================================================================================================================================================================
 Package                                     Architecture                            Version                                          Repository                                    Size
=========================================================================================================================================================================================
Installing:
 tftp-server                                 aarch64                                 5.2-43.amzn2023                                  @commandline                                  40 k

Transaction Summary
=========================================================================================================================================================================================
Install  1 Package

Total size: 40 k
Installed size: 216 k
Is this ok [y/N]: y
Downloading Packages:
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :                                                                                                                                                                 1/1
  Installing       : tftp-server-5.2-43.amzn2023.aarch64                                                                                                                             1/1
  Running scriptlet: tftp-server-5.2-43.amzn2023.aarch64                                                                                                                             1/1
  Verifying        : tftp-server-5.2-43.amzn2023.aarch64                                                                                                                             1/1
=========================================================================================================================================================================================
WARNING:
  A newer release of "Amazon Linux" is available.

  Available Versions:

  Version 2023.6.20250211:
    Run the following command to upgrade to 2023.6.20250211:

      dnf upgrade --releasever=2023.6.20250211

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.6.20250211.html

  Version 2023.6.20250218:
    Run the following command to upgrade to 2023.6.20250218:

      dnf upgrade --releasever=2023.6.20250218

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.6.20250218.html

=========================================================================================================================================================================================

Installed:
  tftp-server-5.2-43.amzn2023.aarch64

Complete!
[ec2-user@ip-172-31-69-236 scratch-tftp]$
```
