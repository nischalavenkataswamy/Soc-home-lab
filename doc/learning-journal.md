# Learning Journal

## Day 1

### Goal

Build the foundation of an enterprise Active Directory environment.

### Activities Completed

- Installed Windows Server 2022
- Configured a virtual machine in VirtualBox
- Installed Active Directory Domain Services (AD DS)
- Promoted the server to a Domain Controller
- Created the `corp.local` forest

### Challenges

- Encountered a DNS delegation warning during promotion.
- Initially had a boot issue caused by the installation media/configuration.

### Resolution

- Verified the installation media and completed the domain controller promotion successfully.
- Confirmed the warning was expected in a new forest deployment.

### Key Learning

A Domain Controller is the central authentication server within an Active Directory environment. DNS is a critical dependency for Active Directory because clients rely on it to locate domain services.

### Next Steps

- Build a Windows 11 client
- Join it to the domain
- Create enterprise users
