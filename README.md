# EL_Q1_2K26_CS_Task_2
Elevate Labs task 2 repo


1. Overview of Task 2
This task focuses on learning core operating system security fundamentals using Linux
(Ubuntu/Kali/Fedora) or Windows. The objective is to understand accounts, permissions,
firewalls, processes, and hardening techniques.
2. User Accounts, Permissions, and Access Control
• Linux user types: regular user, root (superuser), system accounts.
• Windows accounts: Administrator, Standard User, Guest.
• File permissions in Linux: read (r), write (w), execute (x) for user/group/others.
• Tools: chmod (change permissions), chown (change ownership), ls -l (view permissions).
• Access Control Lists (ACLs) allow fine-grained permissions (setfacl/getfacl).
3. Administrator vs Standard User Privileges
Administrator/root accounts can install software, manage system settings, and control other
users. Standard users have limited capabilities, reducing risk exposure from malware or
accidental changes.
4. Firewall Configuration
• Linux UFW (Uncomplicated Firewall): enable, allow specific ports, deny incoming traffic.
• Windows Firewall: built-in firewall that controls inbound/outbound traffic with profiles (domain,
private, public).
• Firewalls reduce exposed services and mitigate attacks.
5. Identifying and Managing Services
• View running processes: `ps aux`, `top`, or `htop` (Linux); Task Manager (Windows).
• List active services: `systemctl list-units --type=service` (Linux).
• Disable unnecessary services to reduce the attack surface and resource usage.
6. Best OS Hardening Practices
• Use strong passwords and enable MFA where possible.
• Keep OS fully updated with latest security patches.
• Disable unused ports and services.
• Restrict sudo/root access to only trusted administrators.
• Enable firewall and configure strict rules.
• Enable disk encryption (BitLocker/LUKS).
• Regularly audit logs and monitor system activity.
• Use anti-malware on Windows; use AppArmor/SELinux on Linux where possible.
