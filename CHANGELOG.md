## vyos-1x

## 📦 Uncategorized

- firewall: T5834: Rename 'enable-default-log' to 'default-log'
   - PR: #2651
- T5859: Fixed format of pool range in the accel-ppp config
   - PR: #2693
- dhcp: T3316: Support hostname, DUID and MAC address in reservation
   - PR: #2650
- T5842: Rewritten PPTP to get_config_dict
   - PR: #2695
- T5801: Rewritten L2TP to get_config_dict
   - PR: #2658
- op-mode: T5866: Add command to restart IPv6 RA daemon
   - PR: #2698
- container: T5867: disable healthchecks due to upstream issue
   - PR: #2699
- ddclient: T5852: add missing priority
   - PR: #2703
- smoketest: T5867: extend container tests for IPv4 and IPv6 networks
   - PR: #2710
- nat: T5681: relax wording on non existing interface Warning message
   - PR: #2709
- vyos.template: T5869: first_host_address() does not honor RFC4291 section 2.6.1
   - PR: #2704
- tacacs: T141: Wrap string in double quotes to allow expansion
   - PR: #2715
- T5688: Fixed ip pool migration scripts for l2tp, sstp, pppoe
   - PR: #2711
- system: T5877: Shorten system domain-search config path
   - PR: #2718
- login: T5875: restore home directory permissions when re-adding user account
   - PR: #2716
- ipsec: T1210: add smoketest for remote-access (road-warrior) users
   - PR: #2722
- T5870: ipsec remote access VPN: add x509 (pubkey) authentication.
   - PR: #2707
- dhcp: T3316: Adjust kea lease files' location and permissions
   - PR: #2696



## vyos-build

## 📦 Uncategorized

- container: T5867: upgrade podman to 4.7.2 (Debian Trixie)
   - PR: #480


