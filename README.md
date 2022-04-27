# Example Docker Compose and Ansible configuration for running Adguard

Example configuration for using Adguard using ansible and docker


## Usage

1. Download the [Raspberry Pi Imager](https://www.raspberrypi.org/software/) and flash the latest version of Raspberry Pi OS *Lite*.
2. Ensure you can ssh to your raspberry pi machine via your access key and the ip is correctly setup on hosts.example.yml
3. Run `ansible-playbook playbook.yml --inventory hosts.example.yml`
4. Sit back and wait until you have a fully configured PiHole running in about 5-10 minutes
5. visit adguard dashboard at http://192.168.50.199:3000 
