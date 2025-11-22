# SOA Record Lookup

## Screenshot
![SOA Record Lookup](Networking-nslookup-soa.png)

## Objective
View the Start of Authority (SOA) record for a domain.

## Steps
1. Open PowerShell.
2. Run the command:

       nslookup -type=soa gmail.com

## Observe
- Primary DNS server for the domain.
- Serial number and refresh times for the domain.

## Key Learning
- SOA records provide authoritative information about a domain.
- Useful for understanding DNS zone settings and updates.
