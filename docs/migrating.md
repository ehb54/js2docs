#Migrating from Jetstream1 to Jetstream2

The team is actively working on a migration plan for allocations and resources on Jetstream1 but we are not ready to make that publicly available at this time.

Jetstream1 will remain online through the end of Q1 2022. We will stop accepting any new allocations on Jetstream1 as soon as Jetstream2 enters operations phase. That date is still yet to be determined.

VMs on Jetstream1 will continue running as long as you have a valid allocation there and until it is decommissioned. The TACC cloud of Jetstream1 will likely be taken down in stages prior to the IU cloud, but those timelines are still up in the air, as well.

Migration plans are still under development. We will provide instructions for moving your VMs and possibly have some tools to help facilitate that. It's also highly likely that it will NOT be an entirely automatic process. Volumes will not persist because they are completely separate systems and do not share storage. There will be migration information for that, as well.

Please watch this space and [XSEDE user news](https://www.xsede.org/news/user-news){target=_blank} and mailing lists for announcements about Jetstream2 operations and migration. To ensure that you are receiving all updates to your inbox, login on the page above to manage your XSEDE User News subscriptions. All Jetstream users should be added when they are placed on an allocation, but you may wish to verify so that you don't miss any important migration updates.

#### Important note for CLI users

Jetstream2 uses application credentials for CLI access so CLI users can authenticate using XSEDE credentials. Please see [Setting up the openrc.sh for the Jetstream2 CLI](ui/cli/openrc.md){target=_blank} for instructions generating application credentials and an openrc for Jetstream2.

**Updates will all be made here and shared via XSEDE User News.**
