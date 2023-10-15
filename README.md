<div align="center">
    <h1>NetPractice</h1>
</div>

## Welcome to the NetPractice Tutorial

The **NetPractice** tutorial is a practical exercise designed to help you grasp networking concepts effectively. You will gain experience in configuring small-scale networks and understanding TCP/IP addressing principles.

Your goal is to complete 10 levels (exercises) and showcase your solutions in your Git repository.

## Concepts

### Configuration Guidelines
1. Ensure client IPs do not overlap.
2. Connect clients within the same subnet using switches.
3. Use routers to connect between subnets.
4. Configure the route table from source to destination IP with CIDR (0.0.0.0/0).
5. Restrict internet access for private IPs within these ranges:
    - `10.0.0.0` to `10.255.255.255`
    - `172.16.0.0` to `172.31.255.255`
    - `192.168.0.0` to `192.168.255.255`
6. Avoid using local IPs within the range:
    - `127.0.0.1` to `127.255.255.254`

### Steps to Solve Problems
1. Verify CIDR or Subnet Mask.
2. Check specific client IPs that are assigned.
3. Calculate available IP ranges in subnets.
4. Configure the route table to align with the problem goals.

### Tips for Successful Evaluation

1. Memorize the CIDR table.
2. Practice levels 6 to 10 until the concepts become second nature.

### CIDR Sheet Table

|     | Address |  Host |     Netmask     |
|-----|:-------:|:-----:|:---------------:|
| /30 |    4    |    2  | 255.255.255.252 |
| /29 |    8    |    6  | 255.255.255.248 |
| /28 |   16    |   14  | 255.255.255.240 |
| /27 |   32    |   30  | 255.255.255.224 |
| /26 |   64    |   62  | 255.255.255.192 |
| /25 |  128    |  126  | 255.255.255.128 |
| /24 |  256    |  254  | 255.255.255.0   |
| /18 |  16384  | 16382 | 255.255.192.0   |
| /16 |  65536  | 65534 | 255.255.0.0     |


The subject is in the repo, check it out for better understanding.(PDF)
