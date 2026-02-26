# Test Plan
    This test plan will provide a rubric to compare all three friewalls based on functionality, performance and security each one provides in the same environment. Each firewall will be tested individually within the same topology to ensure fairness. The test will focus
## Port Filtering Tests(nmaps)
    This will test each firewalls ability to manage and secure the target vms ports, denyling and aloowing traffic which are destined to it ports. Nmap scanning will be used to verify whether specific ports are open, closed or filtered demonstrating how effective the firewall is.
## Service/Protocol Blocking Tests(icmp)
    This test will look to examine how well a firewall handele filtering based on protocols specifically ICMP. By blocking or allowing based on protocol the test will check how good each firewall can control and prevent attempts at reconnaissance.
## Traffic Policy Test
    This test assesses how firewalls behave under different default policies, especiall default-allow and default-deny. It evaluates how well the firewall enforces broader level policies while still being reliable conductor of traffic for approved services.
## Logging Tests
    This will evaluate how each firewall logs allowed and blocked traffic attempts. This will show which firewall is able to reliable and consciely record events and offer a clear account. 